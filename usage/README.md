# Table

This component is based on the blueprint of Veams-Components.

## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: table, @tag: component }}
{{#with table.tableWithHead}}
	{{> c-table}}
{{/with}}

{{#with table.tableHeadLeft}}
	{{> c-table}}
{{/with}}

{{#with table.tableWithoutHead}}
	{{> c-table}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @id: scss-import, @tag: component
@import "components/_c-table";
// @INSERT :: END
```
