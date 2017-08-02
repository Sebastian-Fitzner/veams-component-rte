### Include: Page

``` hbs
// @INSERT :: START @id: rte, @tag: component-partial }}
{{#with rte-bp.variations.single}}
	{{> c-rte}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @tag: scss-self-contained-import //
@import "../components/rte/scss/_c-rte";
// @INSERT :: END //
```