# Class 8

Project topic: Me + You

## 🛠️ Hardware

See also: [Creative Coding Notes list](https://github.com/cacheflowe/creative-coding-notes#physical-computing)

Some hardware needs special device drivers. 

* There's not a simple messaging scheme (like Serial communication) that you can replicate without major reverse-engineering. for example:
  * Kinect / Realsense
  * Leap Motion

Some hardware uses system-supported protocols

* Keyboard/mouse [HID](https://en.wikipedia.org/wiki/Human_interface_device) [devices](https://xkeys.com/xkeys.html)
* Webcams - "[UVC](https://en.wikipedia.org/wiki/USB_video_device_class)" means that a camera of video device can be seen as a webcam by your operating system
* [MIDI](http://en.wikipedia.org/wiki/MIDI)
* Network
  - [HTTP](https://medium.com/@jen_strong/the-request-response-cycle-of-the-web-1b7e206e9047)
  - [WebRTC](https://webrtc.github.io/samples/)
  - [WebSocket](http://en.wikipedia.org/wiki/WebSocket)
  - [OSC](http://en.wikipedia.org/wiki/Open_Sound_Control)
* Serial I/O - This is how we talk to custom sensors via Arduino (or other PCB boards)
  * Example: [Epic React: Instant Go](https://cacheflowe.com/code/installation/epic-react-instant-go) treadmill
  * Example: [30 Years of Air](https://cacheflowe.com/code/installation/nike-soho-air-max-screens) - sensor & motors
* Bluetooth - pretty hard to reverse-engineer

Some hardware just uses electrical signals

* Sensor modules
* Motors
* Lighting protocols
  - [ArtNet](https://en.wikipedia.org/wiki/Art-Net) ([Addressable LEDs](https://cacheflowe.com/code/lab/artnet-+-processing))
  - [DMX](https://en.wikipedia.org/wiki/DMX512) ([Example: Zoom simulation](https://cacheflowe.com/code/installation/zoom-centrifuge))
  - [sACN](https://www.lightjams.com/sacn.html)

*show examples*


## 🛠️ Integration & Networking

TODO: UPDATE THIS - it was moved from class 10

You can combine these tools to create larger integrated systems 
  - Miami Heat project example (ArtNet, WebSockets, Realsense, http)

* Local network & web communication:
  * [HTTP](https://medium.com/@jen_strong/the-request-response-cycle-of-the-web-1b7e206e9047)
  * [WebRTC](https://webrtc.github.io/samples/)
  * [UDP](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/)
  * [WebSocket](http://en.wikipedia.org/wiki/WebSocket)
  * [OSC](http://en.wikipedia.org/wiki/Open_Sound_Control)
    * [osculator](https://osculator.net/)
  * [ZeroMQ](http://zeromq.org)
* Hardware device communication:
  * [Serial](https://editor.p5js.org/cacheflowe/sketches/F7GG8vuEy)
  * [MIDI](http://en.wikipedia.org/wiki/MIDI)
    * [MIDI Translator (OS X)](https://www.bome.com/products/miditranslator)
    * [iConnectMIDI2+](https://www.iconnectivity.com/products/midi/iconnectmidi2plus)
  * Lighting
    * [ArtNet](https://en.wikipedia.org/wiki/Art-Net)
    * [DMX](https://en.wikipedia.org/wiki/DMX512)
    * [Doug Fleenor Design products](http://www.dfd.com/index.html)
    * [sACN](https://www.lightjams.com/sacn.html)
  * Shared textures between apps
    * [Spout](http://spout.zeal.co/)
    * [Syphon](http://www.syphon.v002.info/)
    * [CamTwist](http://camtwiststudio.com/)
  * Video streaming
    * [RTP](https://en.wikipedia.org/wiki/Real-time_Transport_Protocol)
    * [NDI](https://www.ndi.tv/)
    * [WebRTC](https://webrtc.org/)


## 🛠️ Computer vision

* [@ Wikipedia](https://en.wikipedia.org/wiki/Computer_vision)
* p5js CV examples
  * https://github.com/kylemcdonald/cv-examples (need to change p5js version number)
* Processing OpenCV [library](https://github.com/atduskgreg/opencv-processing) - older classic CV algorithms
* Basic, [custom CV](https://cacheflowe.com/code/lab/webcam-experiments)
* Interesting cameras:
  * Depth (Kinect / Realsense)
  * [High framerate](https://www.edgertronic.com/)
  * [Thermal](https://groupgets.com/manufacturers/getlab/products/purethermal-2-flir-lepton-smart-i-o-module)
  * [Infrared](https://www.amazon.com/SVPRO-Outdoor-Waterproof-Surveillance-Android/dp/B07C2RL8PB/) (night vision)

## 🛠️ Computer vision in p5js

* [Mirrored webcam](https://editor.p5js.org/cacheflowe/sketches/zLpJ56Gi2) - (how to flip/mirror your webcam!)
* [MediaPipe multi-mode tracker](https://editor.p5js.org/orrkislev/sketches/wwLqrnVDt) - [original](https://editor.p5js.org/golan/sketches/0yyu6uEwM)
* [MediaPipe hand tracker](https://editor.p5js.org/lingdong/sketches/1viPqbRMv)
* [MediaPipe facemesh](https://editor.p5js.org/lingdong/sketches/ef6FB-uNq)
* [clmtracker example](https://editor.p5js.org/cacheflowe/sketches/k5331wdu7)
* [headtrackr.js example](https://editor.p5js.org/cacheflowe/sketches/8kel7wkpp)
* [ml5.js FaceApi example](https://editor.p5js.org/ml5/sketches/FaceApi_Video_Landmarks)
* [ml5.js BodyPix segmentation example](https://editor.p5js.org/cacheflowe/sketches/ezqWo10Ye)
* [ml5.js PoseNet skeleton example](https://editor.p5js.org/codingtrain/sketches/ULA97pJXR)
* [ml5.js + p5play game](https://editor.p5js.org/StevesMakerspace/sketches/RLGFfn2pt)
* [Teachable Machine](https://teachablemachine.withgoogle.com/) (code is downloadable)
* [Frame differencing example](https://editor.p5js.org/cacheflowe/sketches/NfXQSVwNmG)

## 📝 Homework:

Listen to an episode from either podcast:

* [Tech+Art](https://podcasts.apple.com/ca/podcast/tech-art/id1480019037) Podcast
* [That's So New Media!?](https://open.spotify.com/show/7MXw99WToC4MbZHwAlaFzB?si=UggW_cRMTwmZKVWeVAfsjw&nd=1)

**Build something with a webcam or other hardware**

* p5js resources
  * [Video Capture example](https://p5js.org/examples/dom-video-capture.html)
  * [ml5.js image classification](https://www.youtube.com/watch?v=D9BoBSkLvFo&vl=en)
* Processing
  * [Shiffman: Capture and Live Video](https://www.youtube.com/watch?v=WH31daSj4nc)
  * [Introduction to Webcam Effects with Processing](https://www.youtube.com/watch?v=6pGEk2dQnss)
* Arduino
  * p5js: use the [Web Serial API](https://web.dev/serial/) with [Justin's example sketch](https://editor.p5js.org/cacheflowe/sketches/F7GG8vuEy) (Chrome only)
    * Show example video
  * Processing: use the `Serial` library
* MIDI (Chrome only)
  * [Justin's example sketch](https://editor.p5js.org/cacheflowe/sketches/xuGYeJnZY)
  * [Justin's example sketch 2](https://editor.p5js.org/cacheflowe/sketches/iFMtaetat)

## 📋 Review code

* Present your 3d sketches

