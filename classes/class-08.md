# Class 8

Project topic: Me + You

## 🛠️ Hardware

See also: [Creative Coding Notes list](https://github.com/cacheflowe/creative-coding-notes#physical-computing)

Some hardware needs special device drivers

* There's not a simple messaging scheme (like Serial communication) that you can replicate without major reverse-engineering. for example:
  * Kinect / Realsense
  * Leap Motion

Some hardware uses electrical signals and basic data transmission

* Arduino / Raspberry Pi sensors & output devices


## 🛠️ Integration & Networking

* Keyboard/mouse [HID](https://en.wikipedia.org/wiki/Human_interface_device) 
  * [xkeys devices](https://xkeys.com/xkeys.html)
  * [Arduino Leonardo](https://forum.arduino.cc/t/using-arduino-as-a-usb-hid/504918/7)
* Webcams - "[UVC](https://en.wikipedia.org/wiki/USB_video_device_class)" means that a camera of video device can be seen as a webcam by your operating system
* [MIDI](http://en.wikipedia.org/wiki/MIDI)
* Network protocols
  * [HTTP](https://medium.com/@jen_strong/the-request-response-cycle-of-the-web-1b7e206e9047)
  * [WebRTC](https://webrtc.github.io/samples/)
  * [WebSocket](http://en.wikipedia.org/wiki/WebSocket)
  * [OSC](http://en.wikipedia.org/wiki/Open_Sound_Control)
    * [osculator](https://osculator.net/)
  * [MQTT](https://en.wikipedia.org/wiki/MQTT)
  * [ZeroMQ](http://zeromq.org)
  * [UDP](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/)
* Serial I/O - This is how we talk to custom sensors via Arduino (or other PCB boards)
  * Example: [Epic React: Instant Go](https://cacheflowe.com/code/installation/epic-react-instant-go) treadmill
  * Example: [30 Years of Air](https://cacheflowe.com/code/installation/30-years-of-air) - sensor & motors
* Wireless protocols
  * [Bluetooth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API) (can be hard to work with)
  * [RFID](https://www.instructables.com/Arduino-Wiring-and-Programming-of-RFID-Sensor/)
    * [NFC](https://en.wikipedia.org/wiki/Near-field_communication)
  * [IR](https://roboticsbackend.com/arduino-ir-remote-controller-tutorial-setup-and-map-buttons/)
  * [Zigbee](https://docs.arduino.cc/retired/getting-started-guides/ArduinoWirelessShieldS2/)
* Lighting protocols
  * [ArtNet](https://en.wikipedia.org/wiki/Art-Net) ([Addressable LEDs](https://cacheflowe.com/code/lab/artnet-+-processing))
  * [DMX](https://en.wikipedia.org/wiki/DMX512) ([Example: Zoom simulation](https://cacheflowe.com/code/installation/zoom-centrifuge))
  * [sACN](https://www.lightjams.com/sacn.html)
  * [WLED](https://kno.wled.ge/)
* Shared textures between apps
  * [Spout](http://spout.zeal.co/)
  * [Syphon](http://www.syphon.v002.info/)
* Video streaming
  * [RTP](https://en.wikipedia.org/wiki/Real-time_Transport_Protocol)
  * [NDI](https://www.ndi.tv/)
  * [WebRTC](https://webrtc.org/)


You can use these protocols to create larger integrated systems!


## 🛠️ Computer vision

* [@ Wikipedia](https://en.wikipedia.org/wiki/Computer_vision)
* p5js CV examples
  * https://github.com/kylemcdonald/cv-examples (need to change p5js version number)
* Processing OpenCV [library](https://github.com/atduskgreg/opencv-processing) - older classic CV algorithms
* Basic, [custom CV](https://cacheflowe.com/code/lab/webcam-experiments)
* Interesting cameras:
  * Depth ([Kinect](https://www.orbbec.com/products/tof-camera/femto-mega/) / [Realsense](https://www.intel.com/content/www/us/en/architecture-and-technology/realsense-overview.html))
  * [High framerate](https://www.edgertronic.com/)
  * [Thermal](https://groupgets.com/manufacturers/getlab/products/purethermal-2-flir-lepton-smart-i-o-module)
  * [Infrared](https://www.amazon.com/SVPRO-Outdoor-Waterproof-Surveillance-Android/dp/B07C2RL8PB/) (night vision)

## 🛠️ Computer vision in p5js

* [Mirrored webcam](https://editor.p5js.org/cacheflowe/sketches/zLpJ56Gi2) - (how to flip/mirror your webcam!)
* [MediaPipe multi-mode tracker](https://editor.p5js.org/orrkislev/sketches/wwLqrnVDt) - [original](https://editor.p5js.org/golan/sketches/0yyu6uEwM)
* ml5 [examples](https://editor.p5js.org/ml5/sketches)
  * [handPose-parts](https://editor.p5js.org/ml5/sketches/DNbSiIYKB)
  * [handPose-keypoints](https://editor.p5js.org/ml5/sketches/QGH3dwJ1A)
    * [More info](https://github.com/tensorflow/tfjs-models/blob/master/hand-pose-detection/README.md#keypoint-diagram)
  * [MediaPipe hand tracker](https://editor.p5js.org/lingdong/sketches/1viPqbRMv)
  * [faceMesh-shapes-from-parts](https://editor.p5js.org/ml5/sketches/6qj0M3ElM)
  * [faceMesh-parts-bounding-box](https://editor.p5js.org/ml5/sketches/F9jRILxn2)
  * [faceMesh-keypoints-from-parts](https://editor.p5js.org/ml5/sketches/EjynWxazD4)
  * [faceMesh-bounding-box](https://editor.p5js.org/ml5/sketches/fMCIspRD7_)
  * [bodySegmentation-select-body-parts](https://editor.p5js.org/ml5/sketches/R5rug0HKk)
  * [bodyPose-skeleton](https://editor.p5js.org/ml5/sketches/hMN9GdrO3)
  * [ml5.js PoseNet skeleton example](https://editor.p5js.org/codingtrain/sketches/ULA97pJXR)
  * [ml5.js BodyPix segmentation example](https://editor.p5js.org/cacheflowe/sketches/ezqWo10Ye)
  <!-- * [ml5.js + p5play game](https://editor.p5js.org/StevesMakerspace/sketches/RLGFfn2pt) -->
* [Teachable Machine](https://teachablemachine.withgoogle.com/) (code is downloadable)
* [Frame differencing example](https://editor.p5js.org/cacheflowe/sketches/NfXQSVwNmG)

## 📝 Homework:

Listen to an episode from either podcast:

* [Tech+Art](https://podcasts.apple.com/ca/podcast/tech-art/id1480019037) Podcast
* [That's So New Media!?](https://open.spotify.com/show/7MXw99WToC4MbZHwAlaFzB?si=UggW_cRMTwmZKVWeVAfsjw&nd=1)

**Build something with a webcam or other hardware**

* p5js resources
  * [Video Capture example](https://p5js.org/examples/imported-media-video-capture/)
  * [ml5.js image classification](https://www.youtube.com/watch?v=pbjR20eTLVs)
    * From: [Beginners Guide to Machine Learning in JavaScript](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
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
