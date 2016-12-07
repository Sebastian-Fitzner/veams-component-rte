### Include: Page

``` hbs
// @INSERT :: START @id: rte, @tag: component-partial }}
{{#with rte-bp.single}}
	{{> c-rte}}
{{/with}}

{{#with rte-bp.full}}
		{{> c-rte}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @tag: scss-import //
@import "components/_c-rte";
// @INSERT :: END //

// @INSERT :: START @tag: scss-import-self-contained //
@import "../templating/partials/components/rte/scss/_c-rte";
// @INSERT :: END //
```