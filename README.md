**Project: Simple HTML and CSS Animation**

**Description:**
This project demonstrates a basic HTML and CSS animation. It features a blinking cursor effect on a text element. The animation is achieved using CSS keyframes and the `animation` property.

**Prerequisites:**
- Basic understanding of HTML and CSS
- Familiarity with CSS animations

- The `<div id="main">` element serves as the container for the animation.
   - Inside this container, there are two elements:
     - `<div class="cursor">`: This element represents the blinking cursor.
     - `<h1>prathamesh</h1>`: This is the text element that will be animated.

2. **CSS:**
   - The CSS file contains the styles for the cursor animation.
   - The `*` selector resets all default browser styles and sets the font family to 'Gilroy' and the text color to white.
   - The `html` and `body` elements are set to `height` and `width` of 100%, ensuring that the animation covers the entire screen.
   - The `#main` element has a `height` and `width` of 100%, a background color of black, and is centered both horizontally and vertically using `flex`.
   - The `.cursor` class defines the styles for the cursor animation. It has a `height` and `width` of 20px, a white background color, a `mix-blend-mode` of `difference`, and a border-radius of 50% to create a circular shape.
   - The `h1` selector sets the font size to 9vw and the font weight to 900, making the text large and bold.

**Usage:**
To use this animation, simply include the CSS file in your project and add the `.cursor` class to the element you want to apply the animation to.

**Customization:**
You can customize the animation by modifying the CSS properties, such as the size, color, and blend mode of the cursor.

**Conclusion:**
This project provides a simple yet effective way to add a touch of visual interest to your website or application. With its easy implementation and customizable options, it's a great choice for designers and developers looking to enhance their user experience.

 **JavaScript Code:**
   - The JavaScript code starts by selecting the `main` and `.cursor` elements from the HTML using the `querySelector` method.
   - It then adds an event listener to the `main` element, specifically listening for `mousemove` events.
   - Inside the event listener function, the code retrieves the current mouse position (`dets.x` and `dets.y`) from the event details.
   - The code dynamically updates the position of the `.cursor` element by setting its `left` and `top` CSS properties to the current mouse position.

**Usage:**
To use this code, simply include the JavaScript file in your HTML document and ensure that the `main` and `.cursor` elements are present in the HTML structure. When you move the mouse over the webpage, the visual cursor element will follow the mouse cursor's position in real time.

**Note:**
This code provides a basic implementation of a cursor follower. You can extend and customize it to add additional features or modify the visual appearance of the cursor element as per your requirements.

