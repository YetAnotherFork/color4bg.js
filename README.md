![color4bg.js](https://color4bg.com/static/images/github/01-logo.jpg)

# color4bg.js
generate dynamic, abstract, and visually stunning background images for your web pages using WebGL and JavaScript.

## Demo
Please visit: [color4bg.com](https://www.color4bg.com)

![color4bg.js](https://color4bg.com/static/images/meta-og-image.jpg)


## Features
- Customizable Colors: You can specify an array of up to 6 colors that will be used to generate the background pattern.
- Dynamic Animation: The generated background can be set to loop, creating a mesmerizing, fluid animation.
- Consistent Patterns: By providing a seed value, you can ensure that the same pattern is generated every time, making it easy to integrate into your web design.
- Easy Integration: Simply import the **Bg class and create an instance with your desired settings.


## Usage
To use color4bg.js, follow these steps:

1. Import the AbstractShapeBg module:
```javascript
import { AbstractShapeBg } from "../build/jsm/AbstractShapeBg.module.js"
```

2. Create an instance of AestheticFluidBg (or any other Bg) with your desired settings:
```javascript
let colorbg = new AestheticFluidBg({
    dom: "box",
    colors: ["#D1ADFF", "#98D69B", "#FAE390", "#FFACD8", "#7DD5FF", "#D1ADFF"],
    seed: 1000,
    loop: true
})
```

- dom: The DOM element where the background should be attached.
- colors: An array of up to 6 hexadecimal color values.
- seed: A numerical value used to generate a consistent pattern.
- loop: A boolean value that determines whether the background should loop or not.


## License
This project is licensed under the MIT License.
