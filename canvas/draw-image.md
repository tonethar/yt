# Resources for Draw Image Tutorial
- Tags: canvas, drawImage, translate, rotate, scale, preloader

[**I. Links**](#i-links)

[**II. Start Code**](#ii-start-code)

[**III. Files**](#iii-files)

[**IV. Notes**](#iv-notes)

[**V. References**](#v-references)

---

## I. Links
- YouTube Video -->

---

## II. Start Code

**canvas-draw-image.html**

```html

```

---

## III. Files
- [tiger.png](../_files/tiger.png) image

---

## IV. Notes

### 1. What is canvas?
- *"The Canvas API provides a means for drawing graphics via JavaScript and the HTML <canvas> element. It can be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing"*

### 2. Drawing images onto the canvas
  - We can draw bitmap images into a `<canvas>` tag. The source of the image could be an `<img>` tag, an `Image()` object, a SVG `<image>` element, a frame of a `<video>` element, or another `<canvas>` element
  - The method we will use is [ctx.drawImage()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage)
    - this method can be used to draw a whole image, or just a part of it. It can also be used to scale the image either up or down in size
   
### 3. Preloading images
- Before we can draw an image, the browser has to load it into your computers memory from either a local disk, or from a web server
- If we try to use JavaScript to draw the image onto the canvas before it's loaded, we won't get an error message, instead it will fail silently and not draw the image

---

## V. References
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API
- https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillStyle
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillRect
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/drawImage
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/translate
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/rotate
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/scale
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/PI

