| Name | Type   | Required | Description |
|------|--------|----------|-------------|
| text | string | true     | If `html` is set, this is not required. Text for the button or link. If `html` is provided, the `text` argument will be ignored and `element` will be automatically set to `button` unless `href` is also set, or it has already been defined. This argument has no effect if `element` is set to `input`. |
| html | string | true     | If `text` is set, this is not required. HTML for the button or link. If `html` is provided, the `text` argument will be ignored and `element` will be automatically set to `button` unless `href` is also set, or it has already been defined. This argument has no effect if `element` is set to `input` |
| type | string | true     | Type of `input` or `button` – `button`, `submit` or `reset`. Defaults to `submit`. This has no effect on `a` elements. |
| name | string | true     | Name for the  `button` |
| value | string | true    | Value for the `button` |
| element | string | false |  Whether to use an `input`, `button` or `a` element to create the button. In most cases you will not need to set this as it will be configured automatically if you use `href` or `html` |
| id   | string | false   | ID for the `button` |
| classes | string | false | Classes to add to the button component |
| attributes | object | false | HTML attributes (for example data attributes) to add to the button component |
| disabled   | boolean | false   | Whether the button should be disabled.  `disabled` and `aria-disabled` attributes will be set automatically. |
| href | string | false | The URL that the button should link to. If this is set, `element` will be automatically set to `a` if it has not already been defined |