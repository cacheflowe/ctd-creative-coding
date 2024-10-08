# Class 7

Project topic: Connected Canvas

## 🛠️ Command-Line Interface (CLI)

[CLI cartoon](../images/command-line.png)

* [Different shells](https://en.wikipedia.org/wiki/Command-line_interface)
* vs. [GUI](https://en.wikipedia.org/wiki/Graphical_user_interface)
* Setup & config
  * OS X (also Linux)
    * [Bash](https://www.gnu.org/software/bash/) (Bourne Again SHell)
    * [zsh](http://zsh.sourceforge.net/) (Z shell - the new OS X default)
  * Windows
    * [Command Shell](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)
    * [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/overview?view=powershell-7)
    * [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (Windows Subsystem for Linux)

Why use CLI?

* Automation
  * Convert files
  * Batch process files
  * Find files on your hard drive, or text within files
  * Make web requests (`curl`)
  * Start your app on machine startup
* More powerful & custom commands
* Tools are almost all free & open-source
* Media conversion tools
  * [imagemagick](https://imagemagick.org/index.php)
  * [ffmpeg](https://ffmpeg.org/)
  * [SoX](http://sox.sourceforge.net/)
  * [media-utility-scripts](https://github.com/cacheflowe/media-utility-scripts)
* (Web) Servers
  * [Node.js](https://nodejs.org/)
  * [Beginner's Series to: Node.js](https://www.youtube.com/playlist?list=PLlrxD0HtieHje-_287YJKhY8tDeSItwtg#begnodejs)

How to use it?

* Install your tools with a package manager:
  * [Homebrew](https://brew.sh/) for Mac
  * [Chocolatey](https://chocolatey.org/) or [Scoop](https://scoop.sh/) for Windows
  * [apt](https://manpages.ubuntu.com/manpages/trusty/man8/apt.8.html) for Linux (Ubuntu)
  * Or custom installation when necessary (usually just copying some files onto your computer)
* Navigate to somewhere on your computer
* Run a command!
  * Each `command` is basically a function that can take parameters, just like in JavaScript
  * Ask Google how to do something with `bash` or `zsh` or `Windows Command Prompt 🤢`
  * Write your command into the terminal
  * Or write more complex scripts into a text file, and run your text file from the command line

## 🛠️ Nodejs

What is Node?

* Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.
* `npm` - Node Package manager

Use cases

* Web Server
* Build tools & automations
* WebSocket server
* Batch processing tasks
* CLI tasks in a friendlier environment

Node Resources

* [Introduction to Node.js](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs)
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
  * [Cached Geometry](https://github.com/davepagurek/p5.buildGeometry)
  * [Drawing the pixels to the screen](https://xem.github.io/articles/images/webgl-guide/workflow.png)

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
  * Start with `WEBGL` (p5js) or `P3D` (Processing) mode
    * In p5js, this move the coordinate system to the center of the screen
  * Use `box()`, `sphere()` and other 3d primitive functions to create shapes
    * p5js has additional 3d shapes like `torus()`
* Stretch goals
  * Create your own 3d geometry with `beginShape()`, `vertex()`, and `endShape()`

## 📋 Review code

* Present your data visualizations
