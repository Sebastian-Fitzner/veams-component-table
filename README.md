<p align="right">
    <a href="https://badge.fury.io/js/@veams/component-table"><img src="https://badge.fury.io/js/@veams/component-table.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Table

## Description

The `<table>` element represents data with more than one dimension, in the form of a table.

The specs says:

> Tables have rows, columns, and cells given by their descendants. The rows and columns form a grid; a table's cells must completely cover that grid without overlap.

Tables must not be used as layout aids

-----------

## Installation

### Installation with Veams

``` bash
veams install component table
```
``` bash
veams -i c table
```

-----------

## Fields

### `table.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- | :---: |:---: | :--- |
| settings.tableContextClass | String | `default` | Context class of component. |
| settings.tableClasses | String | | Modifier classes for component. |

#### Content

| Parameter | Type | Description |
|:--- |:---:|:--- |
| content.tableCaption | String | A caption for the table. |
| content.tableHeader | Object | An object which contains the headings. |
| content.tableHeader.tableRows | Array | Rows in header. |
| content.tableBody | Object | An object which contains the body. |
| content.tableBody.tableRows | Array | Rows in body. |

### `table__row.hbs`

#### Settings

| Parameter | Type | Description |
|:--- |:---:|:--- |
| settings.trClass | String | Row classes. |

#### Content

| Parameter | Type | Description |
|:--- |:---:|:--- |
| content.tableCells | Array | Table cells. |

### `table__cell.hbs`

#### Settings

| Parameter | Type | Description |
|:--- |:---:|:--- |
| settings.thTag | Boolean | Definition of th or td. |
| settings.cellClass | String | Cell classes. |

#### Content

| Parameter | Type | Description |
|:--- |:---:|:--- |
| content.cellContent | String | Cell content. |
