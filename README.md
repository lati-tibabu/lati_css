## lati_css - A CSS Utility Library for Effortless Styling

**lati_css** is a lightweight CSS utility library designed to make styling faster and more efficient. It provides a collection of pre-defined utility classes that allow you to apply common styles with just a few words, making your code cleaner and more readable.

**Installation**

To use lati_css, first install it via npm:

```bash
npm install lati_css
```

**Usage**

Import lati_css into your project:

```JavaScript
import React from 'react';
import 'lati_css';

const LatiCssExample = () => {
  return (
    <div className="flex-row gap-10 p-20">
      <div className="w-50p h-200px back-color-blue80 br-10"></div>
      <div className="w-50p h-200px back-color-red80 br-circle"></div>
    </div>
  );
};

export default LatiCssExample;
```

Explanation:

Import React: This imports the React library, essential for creating React components.

Import CSS: This line imports your lati_css.css file, which contains the utility classes you want to use.

Create a Functional Component: LatiCssExample is a functional component in React, a simple way to define UI elements.

JSX Structure: The component returns JSX, which is a syntax extension for JavaScript that lets you write HTML-like structures within your code.

className: The className attribute is used to apply the lati_css utility classes to HTML elements.

flex-row: creates a flex container with row direction.

gap-10: adds a 10px gap between flex items.

p-20: applies 20px padding on all sides.

w-50p: sets the width to 50% of the parent container.

h-200px: sets the height to 200 pixels.

back-color-blue80: sets the background color to a blue shade from your CSS.

br-10: sets the border-radius to 10 pixels.

br-circle: sets the border-radius to 50% to create a circle.

How to Use:

Create a React project (using Create React App or similar).

Put the above code into a file, for example, LatiCssExample.js.

Import and render the component in your app's root file (like App.js):

```JavaScript
import React from 'react';
import LatiCssExample from './LatiCssExample';

function App() {
  return (
    <div>
      <LatiCssExample />
    </div>
  );
}

export default App;
```

Run your React app. You should see the two colored divs rendered according to the lati_css utility classes.

This provides a more React-specific way to showcase the use of lati_css within your documentation.

**Utility Classes**

lati_css offers a wide range of utility classes for various styling aspects. Here are some examples:

**Display Modes**

- `.flex-row`: Sets display to flex with row direction.
- `.flex-column`: Sets display to flex with column direction.

**Padding**

- `.p-1` to `.p-50`: Applies padding values from 1px to 50px on all sides.
- `.pt-1` to `.pt-50`: Applies padding-top values from 1px to 50px.
- `.pb-1` to `.pb-50`: Applies padding-bottom values from 1px to 50px.
- `.pr-1` to `.pr-50`: Applies padding-right values from 1px to 50px.
- `.pl-1` to `.pl-50`: Applies padding-left values from 1px to 50px.

**Margin**

- `.m-1` to `.m-50`: Applies margin values from 1px to 50px on all sides.
- `.mt-1` to `.mt-50`: Applies margin-top values from 1px to 50px.
- `.mb-1` to `.mb-50`: Applies margin-bottom values from 1px to 50px.
- `.ml-1` to `.ml-50`: Applies margin-left values from 1px to 50px.
- `.mr-1` to `.mr-50`: Applies margin-right values from 1px to 50px.

**Gap**

- `.gap-1` to `.gap-100`: Applies gap values from 1px to 100px to elements within a flex container.

**Width**

- `.w-1p` to `.w-100p`: Sets width from 1% to 100% of parent container.
- `.w-5px` to `.w-1000px`: Sets width in pixels with increments of 5px.
- `.w-1s` to `.w-100s`: Sets width in viewports widths (vw) with increments of 1vw.

**Height**

- `.h-1p` to `.h-100p`: Sets height from 1% to 100% of parent container.
- `.h-5px` to `.h-1000px`: Sets height in pixels with increments of 5px.
- `.h-1s` to `.h-100s`: Sets height in viewports heights (vh) with increments of 1vh.

**Border Radius**

- `.br-1p` to `.br-100p`: Sets border-radius in percentage with increments of 1%.
- `.br-1px` to `.br-100px`: Sets border-radius in pixels with increments of 1px.
- `.br-circle`: Sets border-radius to 50% creating a circle.
- `.br-none`: Sets border-radius to 0.

**Border Width**

- `.bw-1px` to `.bw-100px`: Sets border-width in pixels with increments of 1px.
- `.bw-thin`, `.bw-medium`, `.bw-thick`: Sets border-width to default values.
- `.bw-none`: Sets border-width to 0.

**Border Style**

- `.bs-solid`, `.bs-dashed`, `.bs-dotted`, `.bs-double`, `.bs-groove`, `.bs-ridge`, `.bs-inset`, `.bs-outset`: Sets border-style to different styles.
- `.bs-none`, `.bs-hidden`: Sets border-style to none and hidden respectively.

**Border Color**

- `.bc-black`, `.bc-white`: Sets border-color to black and white respectively.
- `.bc-blue100` to `.bc-yellow10`: Sets border-color to predefined color variables with different opacities.

**Color**

- `.color-black`, `.color-white`: Sets color to black and white respectively.
- `.color-blue100` to `.color-yellow10`: Sets color to predefined color variables with different opacities.

**Background**

- `.back-color-black`: Sets background-color to black.
- `.back-color-blue100` to `.back-color-yellow10`: Sets background-color to predefined color variables with different opacities.

**Font Sizes**

- `.text-xs` to `.text-6xl`: Applies font sizes based on predefined variables.

**Line Heights**

- `.line-height-xs` to `.line-height-6xl`: Applies line-height based on predefined variables.

**Font Weights**

- `.font-w-100` to `.font-w-900`: Sets font-weight to specific values.

**Font Styles**

- `.font-italic`, `.font-oblique`, `.font-normal`: Sets font-style to italic, oblique, and normal respectively.

**Text Transform**

- `.text-transform-none`, `.text-transform-uppercase`, `.text-transform-lowercase`, `.text-transform-capitalize`: Applies text transform to elements.

**Letter Spacing**

- `.letter-spacing-0` to `.letter-spacing-100`: Sets letter-spacing in pixels with increments of 5px.

**Word Spacing**

- `.word-spacing-0` to `.word-spacing-100`: Sets word-spacing in pixels with increments of 5px.

**Font Variants**

- `.font-variant-normal`, `.font-variant-small-caps`: Sets font-variant to normal and small-caps respectively.

**Justify Content**

- `.justify-start`, `.justify-center`, `.justify-end`, `.justify-between`, `.justify-around`, `.justify-evenly`: Sets justify-content property to different values.

**Align Items**

- `.align-start`, `.align-center`, `.align-end`, `.align-baseline`, `.align-stretch`: Sets align-items property to different values.

**Flex Property**

- `.flex-1` to `.flex-20`: Sets flex property with incremental values from 1 to 20.
- `.flex-auto`, `.flex-initial`, `.flex-none`: Sets flex property to auto, initial, and none respectively.

**Flex Grow**

- `.flex-grow-1` to `.flex-grow-3`: Sets flex-grow property with incremental values from 1 to 3.
- `.flex-grow-auto`, `.flex-grow-0`: Sets flex-grow property to auto and 0 respectively.

**Flex Shrink**

- `.flex-shrink-1` to `.flex-shrink-3`: Sets flex-shrink property with incremental values from 1 to 3.
- `.flex-shrink-auto`, `.flex-shrink-0`: Sets flex-shrink property to auto and 0 respectively.

**Flex Basis**

- `.flex-basis-auto`, `.flex-basis-0`, `.flex-basis-1`, `.flex-basis-2`, `.flex-basis-3`, `.flex-basis-50`, `.flex-basis-100`: Sets flex-basis property to different values.

**Responsive Design**

lati_css includes media queries to make your styling responsive across different screen sizes. For example, you can use the following classes to adjust layout for mobile devices and tablets:

- **Mobile Devices:**

  - `.flex-row` will automatically stack items vertically on mobile devices (up to 600px).
  - `.w-50p` will become 100% wide on mobile devices.
  - `.p-20` and `.m-20` will be reduced to 10px padding and margin on mobile devices.

- **Tablets:**
  - `.flex-row` will maintain its row layout on tablets (601px to 1024px).
  - `.w-50p` will be 50% wide on tablets.
  - `.p-20` and `.m-20` will be adjusted to 15px padding and margin on tablets.

**Example Usage**

```html
<div class="flex-row gap-10 p-20">
  <div class="w-50p h-200px back-color-blue80 br-10"></div>
  <div class="w-50p h-200px back-color-red80 br-circle"></div>
</div>
```

This HTML snippet creates a row of two divs with a gap of 10px between them. The first div is 50% wide, 200px tall, has a blue background, and rounded corners, while the second div is also 50% wide, 200px tall, has a red background, and is a perfect circle.

**Conclusion**

lati_css is a powerful tool for styling your web pages with ease. Its comprehensive set of utility classes, combined with its responsive design capabilities, makes it a great choice for building modern and efficient websites.
