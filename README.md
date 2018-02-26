[![Build status](https://travis-ci.org/ryersonlibrary/rula-pan-zoom.svg?branch=master)](https://travis-ci.org/ryersonlibrary/rula-pan-zoom)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ryersonlibrary/rula-pan-zoom)

## &lt;rula-expandable-card&gt;

`rula-pan-zoom` is an elements that provides the ability to scale and drag
around any child elements.

### Example

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="rula-pan-zoom.html">
    <custom-style>
      <style is="custom-style">
        rula-pan-zoom {
          height: 500px;
          width: 100%;
      </style>
    </custom-style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<rula-pan-zoom min-scale="0.5" max-scale="5" width="750" height="500">
  <div style="pointer-events: none; background-color: goldenrod; width:740px; height: 490px; border: 5px solid red;"></div>
</rula-pan-zoom>
```

## Usage

The size of the content must be

## Styling

The following custom properties and mxing are available for styling:

Custom propery | Description | Default
---------------|-------------|----------
`--rula-expandable-card-scrim` | Mixin applied to the background when the card is open | `{}`
`--rula-expandable-card-body` | Mixin applied to the body of the card when closed | `{}`
`--rula-expandable-card-modal` | Mixin applied to the modal container when open | `{}`
`--rula-expandable-card` | Mixin applied to the element | `{}`

