# react-color-tools
A Bunch of Tools for work with Colors in CSS way. Eg. Color Picker, Gradient Tool, Color Palette and more.

## How to Install

```js
npm install --save react-color-tools
```

```js
import { NoviColorPicker } from "react-color-tools"

...

```

## Parent Components

### NoviColorPicker

```js
import { NoviColorPicker } from "react-color-tools"

...

```

### NoviGradientTool

```js
import { NoviGradientTool } from "react-color-tools"

...

```

### EnsoPalette

```js
import { EnsoPalette } from "react-color-tools"

...

```

### EnsoColorPicker

```js
import { EnsoColorPicker } from "react-color-tools"

...

```

### EnsoGradientTool

```js
import { EnsoGradientTool } from "react-color-tools"

...

```

### EnsoGradientRuler

```js
import { EnsoGradientRuler } from "react-color-tools"

...

```

## Widget Components

### Wheel

```js
import { Wheel } from "react-color-tools"

...

```

#### value - object { hue, saturation }

#### onChange(hue, saturation)

#### onChangeComplete(hue, saturation)

#### size - diametr of wheel


### Lightness

```js
import { Lightness } from "react-color-tools"

...

```

#### value

#### onChange(hue, saturation)

#### onChangeComplete(hue, saturation)

#### direction - horizontal, vertical

#### width

#### height


### Opacity

```js
import { Opacity } from "react-color-tools"

...

```

#### value

#### onChange(hue, saturation)

#### onChangeComplete(hue, saturation)

#### direction - horizontal, vertical

#### width

#### height


### Hue

```js
import { Hue } from "react-color-tools"

...

```

#### value

#### onChange(hue, saturation)

#### onChangeComplete(hue, saturation)

#### direction - horizontal, vertical

#### width

#### height


### Saturation

```js
import { Saturation } from "react-color-tools"

...

```

#### value

#### onChange(hue, saturation)

#### onChangeComplete(hue, saturation)

#### direction - horizontal, vertical

#### width

#### height


### Swatch

```js
import { Swatch } from "react-color-tools"

...

```

#### color

#### onClick(color)

#### width

#### height


### Input

```js
import { Input } from "react-color-tools"

...

```

#### value

#### format - all, hex, rgb, hsb, r, g, b, a, h, s, b, angle, gradient. For example "rgb+a"

#### onChange(hue, saturation)

#### width

#### height


### Gradient

```js
import { Gradient } from "react-color-tools"

...

```

#### colors

#### active

#### onChange(colors)

#### onChangeComplete(colors)

#### direction

#### width

#### height


### Ruler

```js
import { Ruler } from "react-color-tools"

...

```

#### value

#### type - linear, radial

#### onChange

#### onChangeComplete


## Helpers

### Convertor

```js
import { Convertor } from "react-color-tools"

...

```

#### hexToRgb(hex)

#### hexToHsb(hex)

#### rgbToHex(rgb)

#### rgbToHsb(rgb)

#### hsbToHex(hsb)

#### hsbToRgb(hsb)

### Validator

```js
import { Validator } from "react-color-tools"

...

```

#### isHex(color)

#### isRgb(color)

#### isHsb(color)

#### isRgba(color)

#### isHSBA(color)

#### isColor(color)

#### isLinearGradient(gradient)

#### isRadialGradient(gradient)

#### isGradient(gradient)


### Parser

```js
import { Parser } from "react-color-tools"

...

```

#### parseHex(color)

#### parseRgb(color)

#### parseHsb(color)

#### parseRgba(color)

#### parseHsba(color)

#### parseColor(color)

#### parseLinearGradient(gradient)

#### parseRadialGradient(gradient)

#### parseGradient(gradient)

#### parse(value)
