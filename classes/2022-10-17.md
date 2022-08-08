# Class 8

## 🛠️ Project recap

* Nike - "[Epic React: Instant Go](https://cacheflowe.com/code/installation/epic-react-instant-go)"

## 📋 Review code

* Present your 3d sketches

## 🛠️ Refactoring

* [What is refactoring?](https://refactoring.guru/refactoring)
  * Small/short vs large/long projects
* Articles
  * [5 Quick and Easy Refactoring Tips](https://www.coderslexicon.com/5-quick-and-easy-refactoring-tips/)
  * [Code Refactoring Best Practices: When (and When Not) to Do It](https://www.altexsoft.com/blog/engineering/code-refactoring-best-practices-when-and-when-not-to-do-it/)
* When/why
  * Improve maintainability & readability
  * Can the code be used again? Build a tool!
* Live demo - who will volunteer code?

## 🛠️ Hardware

* [Creative Coding Notes list](https://github.com/cacheflowe/creative-coding-notes#physical-computing)
* Serial I/O - talk to custom sensors & PCB boards
  * React treadmill
  * FF "AR" screen prototype
* Device drivers
  * Kinect
  * Leap Motion
* System-supported protocols
  * Webcams - "[UVC](https://en.wikipedia.org/wiki/USB_video_device_class)" means that a camera can be treated as a webcam
  * Other cameras: Depth, [high framerate](https://www.edgertronic.com/), [thermal](https://groupgets.com/manufacturers/getlab/products/purethermal-2-flir-lepton-smart-i-o-module), [infrared](https://www.amazon.com/SVPRO-Outdoor-Waterproof-Surveillance-Android/dp/B07C2RL8PB/) (night vision)
* LED lighting
  * DMX / Artnet
  * [Zoom simulation](https://cacheflowe.com/code/installation/zoom-centrifuge)
* Integrated systems
  * [Beacon simulation](https://cacheflowe.com/code/installation/the-beacon)

## 🛠️ Computer vision

* [@ Wikipedia](https://en.wikipedia.org/wiki/Computer_vision)
* p5js CV examples
  * https://github.com/kylemcdonald/cv-examples (need to change p5js version number)
* Processing OpenCV [library](https://github.com/atduskgreg/opencv-processing) - older classic CV algorithms
* Basic, [custom CV](https://cacheflowe.com/code/lab/webcam-experiments)

## 🛠️ Computer vision in p5js

* [Mirrored webcam](https://editor.p5js.org/cacheflowe/sketches/zLpJ56Gi2) - (how to flip/mirror your webcam!)
* [MediaPipe hand tracker](https://editor.p5js.org/lingdong/sketches/1viPqbRMv)
* [MediaPipe facemesh](https://editor.p5js.org/lingdong/sketches/ef6FB-uNq)
* [clmtracker example](https://editor.p5js.org/cacheflowe/sketches/k5331wdu7)
* [headtrackr.js example](https://editor.p5js.org/cacheflowe/sketches/8kel7wkpp)
* [ml5.js FaceApi example](https://editor.p5js.org/ml5/sketches/FaceApi_Video_Landmarks)
* [ml5.js BodyPix segmentation example](https://editor.p5js.org/Kennn/sketches/mOziklki0)
* [ml5.js PoseNet skeleton example](https://editor.p5js.org/codingtrain/sketches/ULA97pJXR)
* [Frame differencing example](https://editor.p5js.org/cacheflowe/sketches/NfXQSVwNmG)

## 📝 Homework:

* Listen:
  * [Tech+Art](https://podcasts.apple.com/ca/podcast/tech-art/id1480019037) Podcast
  * [That's So New Media!?](https://podcasts.apple.com/us/podcast/thats-so-new-media/id1499894288)
    * Listen to 2 episodes from either

* Build something with a webcam or other hardware
  * p5js resources
    * [Video Capture example](https://p5js.org/examples/dom-video-capture.html)
    * [ml5.js image classification](https://www.youtube.com/watch?v=D9BoBSkLvFo&vl=en)
  * Processing
    * [Shiffman: Capture and Live Video](https://www.youtube.com/watch?v=WH31daSj4nc)
    * [Introduction to Webcam Effects with Processing](https://www.youtube.com/watch?v=6pGEk2dQnss)
  * Arduino
    * p5js: use the [Web Serial API](https://web.dev/serial/) or the [p5js library](https://github.com/p5-serial/p5.serialport) (requires a local server...)
      * [Justin's example sketch](https://editor.p5js.org/cacheflowe/sketches/F7GG8vuEy)
    * Processing: use the `Serial` library
  * MIDI (Chrome only)
    * [Justin's example sketch](https://editor.p5js.org/cacheflowe/sketches/xuGYeJnZY)
    * [Justin's example sketch 2](https://editor.p5js.org/cacheflowe/sketches/iFMtaetat)


