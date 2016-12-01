<p align="right">
    <a href="https://badge.fury.io/bo/veams-component-table"><img src="https://badge.fury.io/bo/veams-component-table.svg" alt="Bower version" height="20"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Article

## Description

A simple table component.

----

## Fields

### General
- settings.tableContextClass {String} [default] - Just pass a string
- settings.tableClasses {String} - Modifier classes

### Content
- content.tableCaption {String} - A caption for the table
- content.tableHeader {Object} - An object which contains the headings
- content.tableHeader.tableRows {Array} - Rows in header

---

- content.tableHeader.tableRows[].settings.trClass {String} - Row class in header
- content.tableHeader.tableRows[].content.tableCells {Array} - Cells in header

---

- content.tableHeader.tableRows[].content.tableCells[].settings.thTag {Boolean} - Definition of th or td
- content.tableHeader.tableRows[].content.tableCells[].settings.cellClass {Boolean} - Cell class in header
- content.tableHeader.tableRows[].content.tableCells[].content.cellContent {String} - Cell content in header

---

- content.tableBody {Object} - An object which contains the body
- content.tableBody.tableRows {Array} - Rows in body

---

- content.tableBody.tableRows[].settings.trClass {String} - Row class in header
- content.tableBody.tableRows[].content.tableCells {Array} - Cells in header

---

- content.tableBody.tableRows[].content.tableCells[].settings.thTag {Boolean} - Definition of th or td
- content.tableBody.tableRows[].content.tableCells[].settings.cellClass {Boolean} - Cell class in header
- content.tableBody.tableRows[].content.tableCells[].content.cellContent {String} - Cell content in header
