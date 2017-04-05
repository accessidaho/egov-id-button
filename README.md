# \<id-button\>

Idaho button element

## Installation

Add the following to bower.json.

```JSON
{
  "id-button": "https://github.com/accessidaho/egov-id-button.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-button/id-button.html">
```

Add the element and set properties:

```html
<id-button
  color="[success, warning, danger]"
  links="[{'title': 'Link', 'url': 'Url'}]"
  indent
  outline
  >Button Message
</id-button>
```

## Styling

`<id-button>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--id-primary-border` | Default border color | #255dab
`--id-primary-color` | Default background color | #2968c0
`--id-primary-border-hover` | Default border color on hover | #1a4179
`--id-primary-color-hover` | Default background color on hover | #205196
