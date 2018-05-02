## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: table, @tag: component-partial }}
{{#with table.variations.tableWithHead}}
    {{> table content=this.content settings=this.settings}}
{{/with}}
{{! @INSERT :: END }}
```