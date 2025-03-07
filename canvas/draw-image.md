# Canvas `.drawImage()` Tutorial
- Tags: canvas, drawImage, translate, rotate, scale, preloader
- Prereqs: HTML & basic JavaScript literacy, some familiarity with canvas drawing API

[**I. Links**](#i-links)

[**II. Start Code**](#ii-start-code)

[**III. Files**](#iii-files)

[**IV. Notes**](#iv-notes)

[**V. References**](#v-references)

---

## I. Links
- [YouTube Video Link](https://youtu.be/2BdIEL_bCvk)

---

## II. Start Code

**canvas-draw-image.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Canvas Image Draw</title>
  <style>
    canvas{
      border:1px solid black;
    }
  </style>
</head>
<body>
<canvas width="600" height="600"></canvas>
<script></script>
</body>
</html>
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
- If we try to use JavaScript to draw the image onto the canvas before it's loaded, we won't get an explicit error message, but our code will fail to draw the image to the canvas
- We'll discuss when you might not need to pre-load images at all!
- *In a future video I'll demo how to write a function that will preload multiple images files*

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

