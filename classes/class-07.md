# Class 7

## 🛠️ Command-Line Interface (CLI)

[CLI cartoon](../images/command-line.png)

* [Different shells](https://en.wikipedia.org/wiki/Command-line_interface)
* vs. [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface)
* Setup & config
  * OS X (also Linux)
    * [Bash](https://www.gnu.org/software/bash/) (Bourne Again SHell)
    * [zsh](http://zsh.sourceforge.net/) (Z shell - the new OS X default)
  * Windows
    * [Command Shell](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
    * [Powershell](https://learn.microsoft.com/en-us/powershell/scripting/overview)
    * [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) (Windows Subsystem for Linux)

Why use CLI?

* Automation
  * Launch apps/scripts
  * Convert files
  * Batch process files
  * Start your app on machine startup
* Find files on your hard drive, or text within files
* Make web requests (`curl`)
* More powerful & custom commands
* Take advantage of existing command-line tools
* Media conversion tools
  * [imagemagick](https://imagemagick.org/)
  * [ffmpeg](https://ffmpeg.org/)
  * [SoX](http://sox.sourceforge.net/)
  * [media-utility-scripts](https://github.com/cacheflowe/media-utility-scripts)
* (Web) Servers
* CLI tools are almost all free & open-source
* Vibe coding tools like Gemini CLI, Github Copilot, & Claude Code are offered as terminal applications

How to use it?

* Install your tools with a package manager:
  * [Homebrew](https://brew.sh/) for Mac
  * [Chocolatey](https://chocolatey.org/) or [Scoop](https://scoop.sh/) for Windows
  * [apt](https://manpages.ubuntu.com/manpages/trusty/man8/apt.8.html) for Linux (Ubuntu)
  * Or custom installation when necessary (usually just copying some files onto your computer)
* Navigate to somewhere on your computer
* Run a command!
  * Each `command` is basically a function that can take parameters, just like in JavaScript
  * Ask Google or AI how to do something with `bash` or `zsh` or `Windows Command Prompt`/`Powershell`
  * Write your command into the terminal
  * Or write more complex scripts into a text file, and run your text file from the command line

[File paths meme](../images/file-paths-jedi.jpg)

## 🛠️ Nodejs

[The server is down](../images/server-is-down.png)

What is Node?

* [Node.js](https://nodejs.org/) is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.
* `npm` - Node Package manager
* `package.json` - project config file
  * `npm install`
  * `npm run [command]`
  * Use this [example project](https://github.com/benjaminmiles/react-three-vite) to try it out

Use cases

* Web Server & development tools
* WebSocket server
* Build tools & automations
* Batch file-processing tasks
* CLI tasks in a friendlier environment
* General plumbing to connect different apps (http requests, file handling, websocket connections, etc)

Node Resources

* [Node.js](https://nodejs.org/)
* [Introduction to Node.js](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs)
* [Beginner's Series to: Node.js](https://www.youtube.com/playlist?list=PLlrxD0HtieHje-_287YJKhY8tDeSItwtg#begnodejs)
* [Node.js Ultimate Beginner’s Guide in 7 Easy Steps](https://www.youtube.com/watch?v=ENrzD9HAZK4)
* [Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://www.youtube.com/watch?v=TlB_eWDSMt4)
* [Build an API from Scratch with Node.js Express](https://www.youtube.com/watch?v=-MTSQjw5DrM)
* [Node Weekly](https://nodeweekly.com/)
* [The Coding Train topics](https://thecodingtrain.com/tracks/lang/all/topic/node-js)


## 🛠️ 3D Graphics

The Graphics pipeline

* [How do Video Game Graphics Work?](https://www.youtube.com/watch?v=C8YtdC8mxTU)
* [Projection (3D)](https://jsantell.com/3d-projection)
* [WebGL Guide](https://xem.github.io/articles/webgl-guide.html)
* [Learn OpenGL](https://learnopengl.com/)

Basic layout & 3d thinking

* We're using an abstracted tool... It's just a 3rd coordinate ;)
* Live demos
  * [for() loops 3D](https://editor.p5js.org/cacheflowe/sketches/1S7L5IqjO)
  * [3d shapes basic](https://editor.p5js.org/cacheflowe/sketches/6jSCgZm0L)
  * [3d textured sphere w/light](https://editor.p5js.org/cacheflowe/sketches/LJJZUnd9_)
  * [Graphics & textured cube](https://editor.p5js.org/cacheflowe/sketches/T2VXcVI2A)
  * [Disable depth test](https://editor.p5js.org/cacheflowe/sketches/SW763JUky)

## CPU vs GPU

* What tasks are handled on each?
  * Shader code and pixel display operations are handled on the GPU
  * Most of the code that you write is on the CPU, unless you're writing shaders or OpenGL code
    * Under the hood of p5js & Processing, there's a ton of OpenGL/WebGL code, so know how this stuff works is helpful to know what your performance bottlenecks might be
* What's optimized on the GPU
  * It depends on the platform and tools
    * For example, certain parts of web browser rendering happen on the GPU, but differs per browser
  * Textures & texture operations
    * Loading an image file is almost always faster than drawing vector data
  * Cached Geometry with [p5.Geometry](https://p5js.org/reference/p5/p5.Geometry/) and [buildGeometry()](https://p5js.org/reference/p5/buildGeometry/)
  * [Drawing the pixels to the screen](../images/webgl-rendering.png)
* [cpu.land](https://cpu.land/)
* [CPU vs GPU vs TPU vs DPU vs QPU](https://www.youtube.com/watch?v=r5NQecwZs1A)

## 📝 Homework:

Read:

* The WebGL & OpenGL articles above

Watch:

* [Best Of Demoscene 2020 (Playlist)](https://www.youtube.com/watch?v=zWqfX9J9BXI&list=PL9HVvEQXdWVb22aDO98yTbhqE8zy9XaDE)
* [SIGGRAPH 2020: Technical Papers Preview Trailer](https://www.youtube.com/watch?v=jYdMKdRUq_8)
* [SIGGRAPH 2019: Technical Papers Preview Trailer](https://www.youtube.com/watch?v=EhDr3Rs5fTU)
* [SIGGRAPH 2018 Asia: Technical Papers Preview Trailer](https://www.youtube.com/watch?v=wdKpXvF_3AU)

**Build something with a 3rd dimension**

* Steps
  * Start with `WEBGL` mode in p5js
    * This moves the coordinate system to the center of the screen
  * Use `box()`, `sphere()` and other 3d primitive functions to create shapes
    * p5js has additional 3d shapes like `torus()`
* Stretch goals
  * Create your own 3d geometry with `beginShape()`, `vertex()`, and `endShape()`
  * Apply a texture to your geometry
  * Load a 3d model with `loadModel()`
  * Use a shader to create a custom material for your 3d geometry

## 📋 Review code

* Present your data visualizations
