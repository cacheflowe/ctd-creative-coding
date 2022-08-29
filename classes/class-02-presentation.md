# Creative Code
## Class 2 

---

## 🛠️ Drawing tools

* The graphics **context** refers the current image that's displayed, and the underlying technology used to draw and manipulate it, and keep track of it
  * It also refers to the **current state** of the **canvas**
* p5js is built upon the html `<canvas>` [element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas)
  * p5js & Processing draw in a certain type of way
    * Shapes, image, text are the primary tools
    * Compare to drawing tools with scene graphs (Unity, THREE.js)
  * Not the most performant
  * Amazing ease-of-use
  * Very popular to create art and learn graphics techniques

---

## 🛠️ Drawing tools

The graphics **context**

* `WEBGL` mode disclaimer + [example](https://editor.p5js.org/cacheflowe/sketches/UYoSsOaV_)
  * Doesn't use normal `<canvas>` operations
  * WebGL is faster and more capable
  * WebGL is uglier in a lot of cases

---

## 🛠️ Drawing tools

**p5js**

* Professional data viz [example](https://editor.p5js.org/cacheflowe/sketches/sIdQuK_3W)
  * Rounds of design & UX testing
  * Not a common tool for my job, but useful in this case
  * I use Processing for my work

---

## 🛠️ Drawing tools

The graphics **context**

* [Example sketch about context](https://editor.p5js.org/cacheflowe/sketches/Ciw6RMl7G)
* Adjust the following properties on the context before drawing a shape
  * `fill()`
  * `stroke()`
  * `translate()`
    * `push()`
    * `pop()`
  * `scale()`
  * `rotate()`
    * `CORNER` vs. `CENTER` ([example](https://editor.p5js.org/cacheflowe/sketches/nOll3v7bR))

---

## 🛠️ Drawing tools

The graphics **context**

* We've seen many different ways of drawing a shape (`ellipse()`, `rect()`), but let's consider:
  * `image()`
    * Make sure you load the image with `loadImage()` before drawing
    * [Image example (basic)](https://editor.p5js.org/cacheflowe/sketches/H0JGQe2fu)
    * [Image example (advanced)](https://editor.p5js.org/cacheflowe/sketches/DhW4CrQ18)
  * `text()`
    * Custom fonts: Make sure you load the font first
      * [Example](https://editor.p5js.org/cacheflowe/sketches/ZbOawrLPw)
* Advanced `context` topics
  * [Clipping](https://editor.p5js.org/cacheflowe/sketches/-tO_SsjsC)
  * [Dynamic Masking](https://editor.p5js.org/cacheflowe/sketches/Tlx3KwDHI)
    * [Fancier Masking](https://editor.p5js.org/cacheflowe/sketches/l7xQ9dh64)

---

## 🛠️ Iteration

* `for()` loops
  * Good for doing something many times
  * Work hand-in-hand with Arrays
* Nested `for()` loops
  * [Grid 2D](https://editor.p5js.org/cacheflowe/sketches/xsYHe2SY_)
  * [Grid 2D w/labels](https://editor.p5js.org/cacheflowe/sketches/myxKaCofw)
  * [Grid 2D w/objects in array](https://editor.p5js.org/cacheflowe/sketches/U1nSNmcBQ)
  * [Grid 2D: Pixelated video/webcam](https://editor.p5js.org/cacheflowe/sketches/aLybN_TdB)
  * [Grid 3D](https://editor.p5js.org/cacheflowe/sketches/1S7L5IqjO)

---

## 🛠️ Animation

* Exercises:
  * Intro to [basic movement](https://p5js.org/examples/motion-bounce.html)
  * And more [examples/exercises](https://creative-coding.decontextualize.com/changes-over-time/)
* Real-time coding vs scripting or event-based environments
  * `noLoop()` option

---

## 📝 Homework:

* Read:
  * "[Why Love Generative Art?](https://www.artnome.com/news/2018/8/8/why-love-generative-art)" - A history of the medium
* Watch:
  * [Robert Hodgin @ Eyeo 2014](https://vimeo.com/103537259) - watch at least the first 13 minutes
    * If you love this, watch [Robert Hodgin @ Eyeo 2012](https://vimeo.com/45526286)

---

## 📝 Homework:

* Browse & collect inspiration. Post your favorite sketches in Slack!
  * [OpenProcessing](https://www.openprocessing.org/)
  * [CodePen](https://codepen.io/search/pens?q=p5js)
  * [ShaderToy](https://www.shadertoy.com/)
  * [Justin's inspiration links](../docs/inspiration.md)

---

## 📝 Homework:

* Program a [poster](https://www.instagram.com/tim_rodenbroeker/)
  * Use shapes, color, type, images
  * If you're not great with colors, use a [palette generator](https://coolors.co/palettes)
  * Find [inspiration](https://www.google.com/search?q=bauhaus+poster+design) and borrow ideas if you're not a natural designer. If you really want to keep it simple, replicate an existing design, but credit the original designer in the comments.
  * If you are a designer, try to make something more contemporary, or in your own style
  * For stretch goals:
    * Use grids
    * Swap colors with a key press or mouse position
    * Make multiple posters
    * Randomize elements
  * Make your canvas big, and use [this function](https://editor.p5js.org/cacheflowe/sketches/bTaASS9mv) to scale it down, so you can fit it onto screen

---

## 📋 Review code

* Present your ATLAS "A" programs
