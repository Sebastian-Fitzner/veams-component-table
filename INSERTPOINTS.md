
### Include: Page

``` hbs
{{! @INSERT :: START @id: table, @tag: component-partial }}
{{#with table-bp}}
	{{#each variations}}
		{{> c-table content=this.content settings=this.settings}}
	{{/each}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @tag: scss-import
@import "components/_c-table";
// @INSERT :: END

// @INSERT :: START @tag: scss-import-self-contained
@import "../templating/partials/components/table/scss/_c-table";
// @INSERT :: END
```