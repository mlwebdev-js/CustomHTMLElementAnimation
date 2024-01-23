# MyCustomElement Library

## Overview

MyCustomElement Library is an innovative, high-performance JavaScript library focused on creating custom HTML elements utilizing the latest ES6 features. It offers a modular and scalable approach to build reusable web components, complete with encapsulated styling and behavior. Key features include custom CSS animations and efficient DOM manipulation, leveraging ES6 features like rest and spread operators, map, reduce, and filter.

## Features

- **Custom HTML Elements**: Easily create and manage custom HTML elements.
- **CSS Animations**: Add dynamic animations to your custom elements.
- **ES6 Modules**: Utilize modern JavaScript ES6 features for cleaner, more modular code.
- **Animation Controller**: A separate class to manage and control animations on custom elements.

## Installation

Clone the repository to include the MyCustomElement library in your project:

```bash
git clone https://github.com/yourusername/mycustom-element-library.git
```

### Usage

1. **Import the Custom Element**

   In your main JavaScript file or module, import `MyCustomElement`:

   ```javascript
   import { MyCustomElement } from './path/to/MyCustomElement.js';

Use the Custom Element in HTML

```
html
<body>
    <my-custom-element></my-custom-element>
    <button id="animate-btn">Animate</button>
</body>
```
Control Animations with the AnimationController

Import and use AnimationController to interact with the custom element:

```
import { AnimationController } from './path/to/AnimationController.js';
```

```
const animationController = new AnimationController();
document.getElementById('animate-btn').addEventListener('click', () => {
    animationController.triggerAnimation();
});
```

## Documentation
MyCustomElement: This class provides the structure and methods to create a custom HTML element with shadow DOM for style encapsulation.
AnimationController: A utility class to control animations on the MyCustomElement.
Contributing
Contributions are welcome! Please read our Contributing Guide for more information.

 ##License
This project is licensed under the MIT License - see the LICENSE file for details.
