# Classy Button

A standart, but classy, button.

## Installation

The recommended installation method is a [bower](http://bower.io).

```shell
bower install --save classy-button
```

## Usage

Buttons have a few required constraints for proper functionality,
accessibility, and styling:

- Whenever possible, use `button` over `a`.
- Never set `tabindex` on buttons - let the browser automaticaly set that.

```html
<button class="button">Button</button>
<a class="button">A button link</a>
```

Variable | Description
---|---
`@classy-button-namespace` | The namespace uses for classy button (`button` by default).

## License

Licensed under the [MIT license](http://mit-license.org/vitalk).
