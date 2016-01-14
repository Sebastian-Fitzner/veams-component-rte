# slider

This component is based on the blueprint of Veams-Components.

## Usage

### Include: Page

``` hbs
// @INSERT :: START @id: component, @tag: veams-component
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
// @INSERT :: START @id: scss-import, @tag: veams-component
@import "components/_c-rte";
// @INSERT :: END
```
