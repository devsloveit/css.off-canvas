# css.off-canvas by devslove.it

## Installation
We recommend using a package manager to install this widget as a dependency of your project. Please read the docs of the respective package manager if you don't know how to use it.
* [npm](https://www.npmjs.com/package/devsloveit-css.off-canvas): `npm install devsloveit-css.off-canvas`

You can add `--save` as a parameter if you want to add the plugin into your `package.json`.

## Usage
### HTML
Have a look at [codepen](https://codepen.io/devsloveit/pen/VmgEBO).

#### data-comes-from
We are using a data-attribute (e.g. `data-comes-from="right"`) for defining the direction.

### JavaScript
We don't need JavaScript ;-)

### SCSS

#### Mixins
`@include devsloveit-off-canvas-styles();`

##### Options
| Option  | Default | Description |
|---|---|---|
| $background-color | false | Defines the background-color of your container. |
| $helper-background-color | false |  Defines the background-color of your closing-helper. |
| $max-height | false | Should be defined for _top_ or _bottom_ uses. |
| $max-width | false | Should be defined for _left_ or _right_ uses. |
| $transition-time | $devsloveit-off-canvas-transition-time | Is defined in main settings. Can be overwritten by setting a new value to the variable. |
| $transition-type | $devsloveit-off-canvas-transition-type | Is defined in main settings. Can be overwritten by setting a new value to the variable. |
