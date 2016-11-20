# Material-Box-Shadow-Sass-Mixin
A really cool and easy to use SASS (SCSS) mixin to create an interactive Material Design drop shadow.

## Description
This is mixin based on Material Design box shadows with 5 presets and a strength setting.

![Demo Image](https://raw.githubusercontent.com/mattdanielbrown/Material-Box-Shadow-Sass-Mixin/master/Demo-Image-1.png)
![Demo Image Dark Background](https://raw.githubusercontent.com/mattdanielbrown/Material-Box-Shadow-Sass-Mixin/master/Demo-Image-2.png)

**__I'm not the author of this mixin.__**

#### It was created by [Daniel Box](http://codepen.io/dbox/).

**[Check out his live demo on CodePen](http://codepen.io/dbox/pen/JXjezq).**

## Installation
Add the `_material-design-drop-shadow.scss` partial file (which contains the mixin) to your project.

Generally, this will be then be included in your main SCSS file:

```scss
@include path/to/material-design-drop-shadow
```

You're then ready to use the mixins.

## Usage
The mixin defines 5 presets and allows specifying a strength setting.

sample usage:

```scss
div {
  @include material-shadow($z-depth: 3);
}
```

Or...

```scss
.your-selector {
  @include material-shadow(3);
}
```

### Increasing strength for darker backgrounds

sample usage:

```scss
@include material-shadow($z-depth: 3, $strenght: 2);
```
