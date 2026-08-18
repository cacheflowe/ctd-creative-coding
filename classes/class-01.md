# Class 1 

## 📋 Introductions

* Review the [course description](https://github.com/cacheflowe/ctd-creative-coding?tab=readme-ov-file#course-description). This isn't a frontend course!
* Your [instructor](https://cacheflowe.com)
  * Interests: music, graphics, interaction, games
  * Show some projects
* Tutor / Code Helper
* Various skill levels
  * **Everyone**: Learn about the craft, the state of the art, and express yourself creatively with code
  * **Beginners**: I want you to learn to find joy in coding, and get comfortable with tools, techniques, and nomenclature
  * **Advanced**: I want you to dig deep, explore concepts, seek out additional challenges to hone your skills, and build a more robust portfolio
* Expectations of conduct & [ethos](../docs/policies.md#ethos-for-learning-code) for learning code
* See the [original works](../docs/policies.md#original-works) policy

### Student introductions & interests

* What topics are you interested in?
* How can we merge our interests with code?
* Special requests to make this course work for you?

## 📋 What is code?

### Code is software, code is everywhere

* Code is usually written in text files, but there are also node editors and other ways to build interactive software
* Writing code is the practice of building a **web of logic and data**
* [Code isn't hard, but it is frustrating](https://clivethompson.medium.com/programming-isnt-hard-but-it-s-frustrating-6cb740085243)
* Language & [syntax](https://en.wikipedia.org/wiki/Syntax_(programming_languages))
* Most modern languages are [very similar](https://en.wikipedia.org/wiki/Comparison_of_programming_languages)

### Why code?

* Interdisciplinary & creative work
* It's fun and magic!
* Jobs & employment*
* Digital literacy

\* Even if you don't pursue a career in coding, understanding code is increasingly important part of literacy in the digital world

### How to love it

* Find something that speaks to your interests
  * You'll each find your own path with code (languages, career paths)
* Find the magic
* Personal story of failure & persistence in Computer Science

### How to learn it

* Practice! Try, fail, repeat - it's better to start writing bad code than to let yourself get stuck [meme](../images/can-i-code-fast.jpg)
* Self-directed and meandering exploration - this is an important ethos of approaching programming from a creative coding perspective
* [Which language/tool should I learn?](https://twitter.com/shanselman/status/1560431550981804032) Any! [This will change over time.](https://remotesynthesis.com/blog/the-price-of-developer-tools/)
* Where to find answers: break the problem down, ask it in plain English ("how do I make a circle move?"), then search - your AI assistant, Google/YouTube, [docs](https://p5js.org/reference/), [Stack Overflow](https://stackoverflow.com), or each other (Canvas/Slack - since we don't have much class time together, this matters)
* Don't get overwhelmed - some concepts take a long time, and this is a (life)long journey. It's more important to learn the capabilities of the tools than to memorize syntax
* Finally, [let's talk about AI](../docs/learning-with-ai.md)

🔍 *Further*

* [meme](../images/language-rankings-jun-2024.png)
* More places to look: Articles/Blogs/Tutorials, Slacks/Discords where coders talk

### How to do code

* Get an IDE that's good for your language of choice - [VS Code](https://code.visualstudio.com/) for web/general dev, or p5js's own [online editor](https://editor.p5js.org/)
* Type your code into text files (or connect nodes in a node editor), then compile or run your program

🔍 *Further (other languages have their own popular IDEs)*

* Java: [IntelliJ IDEA](https://www.jetbrains.com/idea/) or Eclipse
* C#: [Visual Studio](https://visualstudio.microsoft.com/)
* Swift: [Xcode](https://developer.apple.com/xcode/)
* VS Code has been extended to work with almost any language

## 📋 What is "creative" code?

* It's still just code! But with an emphasis on media, graphics, audio, and interactivity
* "Creative coding", is a buzzword that most commonly refers to:
  * [Generative art](https://github.com/cacheflowe/creative-coding-notes)
  * Interactive installations
  * New Media Art
  * Making games, toys, apps, instruments, or anything **creative**, that's not just a typical website or app
* But, all code is creative!
  * Solving any engineering problem is a creative process
* What kind of creative coder do you want to be?
  * Some [artists](../docs/artists.md) for inspiration
  * Let's use this class to learn, build a portfolio, and make conceptual work. Generative art becomes much more meaningful with an artist statement, a unique personal perspective, or a story to tell.

## 🛠️ Get your tools ready

### p5js (or Processing)

* For p5js, create an account for [the editor](https://editor.p5js.org/)
  * Get the [VS Code](https://code.visualstudio.com/) IDE, and then install the [p5js extension](https://marketplace.visualstudio.com/items?itemName=samplavigne.p5-vscode)
  * There's a good setup explainer here [p5js in VS Code](https://www.youtube.com/watch?v=OGB4WDw9iJA)
  * If you use an external editor for p5js, please paste your code back into the p5js web editor to turn in your assignments
* For Processing, [install the IDE](https://processing.org/download/)
* If you'd like to use other tools like Unity, TouchDesigner, THREE.js, Openframeworks:
  * I can help during office hours, but if I don't have experience with the tool, you'll be on your own
  * I expect video documentation of your projects, since you can't turn them in via a link to the p5js editor. Use Canvas to pass in your video documentation if you go this route
  * Use [GitHub](https://github.com/) to post your code and upload a video to Canvas
* Slack
  * Use this to help each other out - my coworkers and I use Slack to chat about engineering problems
* Screen capture - you'll need this to document your work
  * OS X: [Quicktime](https://support.apple.com/en-us/HT208721)
  * Windows 10: Windows **Snipping Tool** or [Xbox Game Bar](https://support.microsoft.com/en-us/help/4027180/windows-10-record-a-game-clip-with-xbox-game-bar)

## 🛠️ Code basics overview

### Basic coding concepts:

* Variables
* Functions
* Conditionals (if/else)
* [for() loops](https://en.wikipedia.org/wiki/For_loop#Timeline_of_the_for-loop_syntax_in_various_programming_languages)
* Arrays
* Objects
* Classes

[for() loops were invented in 1972](../images/for-loop-50-yo.png)

Every language has these features - the first goal is to understand these constructs & tools

If you're *not* comfortable with these concepts yet, come to office hours and study the following links 👇

## 🛠️ Live demo (10 min): draw some shapes

* Pull up the [p5js editor](https://editor.p5js.org/) together and build a tiny preview of tonight's homework
* `background()`, `fill()`, a couple of shapes (`rect()`, `ellipse()`, `triangle()`) - just enough to show it's not scary
* This is the shape of every homework to come: open the editor, try something small, see it work

## 📝 Homework:

### Get familiar (or refamiliarize) with basic programming concepts

* If you have little or no code experience, start here with sections 1-5:
  * [Code! Programming with p5.js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) 
* Go through the 1st section of articles at [Welcome to Coding](https://happycoding.io/tutorials/p5js/)
  * Even if you're comfortable with the basic concepts, there are lots of important tips within.
* And a great course overview about [Programming Design Systems](http://printingcode.runemadsen.com/) by Rune Madsen, which is now its [own website](https://programmingdesignsystems.com/color/color-schemes/index.html)
* Books
  * https://natureofcode.com/
  * https://www.aesthetic-programming.net/index.html
* [p5.js examples](https://p5js.org/examples/)
  * [p5.js v2](https://github.com/processing/p5.js-compatibility)
* Prepare your tools & workspace
* Prepare to share & document your work

### The actual assignment

* Build an [ATLAS logo](https://clementzheng.github.io/atlas-wordmark/index.html) "**A**" of your choice with [code](https://editor.p5js.org/cacheflowe/sketches/igKe9eDoB). Use basic drawing tools to set colors and create shapes:
  * w/p5js:
    * Color
      * [background()](https://p5js.org/reference/p5/background)
      * [fill()](https://p5js.org/reference/p5/fill)
      * [noFill()](https://p5js.org/reference/p5/noFill)
      * [noStroke()](https://p5js.org/reference/p5/noStroke)
    * Shapes
      * [Triangles](https://p5js.org/reference/p5/triangle)
      * [Rectangles](https://p5js.org/reference/p5/rect) and [Quads](https://p5js.org/reference/p5/quad)
      * [Ellipses](https://p5js.org/reference/p5/ellipse)
      * [Polygons](https://p5js.org/reference/p5/vertex)
      * [Bezier](https://p5js.org/reference/p5/bezier) or [Quadratic](https://p5js.org/reference/p5/quadraticVertex) curves

### If this is easy for you, try some stretch goals:

* Add animation or interactivity
* Get creative with color
* Build an "A" with different drawing functions. For example: ellipse() circle() and a rounded rect() can all draw the same shape
* Make your own "A" designs
* Build several different "A" logos
  * Explore p5 API and learn how to create even more shapes
* Build the "A" in a larger, designed layout with code
* Morph one "A" to another
* Make it "pixel-perfect": Load an image and draw your shapes on top to make sure it's perfect
* Make an interesting background - use an image or generate a pattern
* Build a larger story or concept around the "A"
* Use a different tool (Shadertoy, TouchDesigner, Unity) to make an "A"

### Turn in your work via Canvas

* Post the link to your code on https://editor.p5js.org/
* Add a description of your intent, your successes, and failures
* If you're using a different tool, upload a video to Canvas or post a link to a video on YouTube (or elsewhere) and post your code to Canvas
* If you use tutorials or other resources, please credit them in your comments. I don't care if your work is *impressive*, I care that you're *learning* and *practicing*. It's okay to borrow other people's code and use AI tools, but don't pretend that it's your own. Attribution is an important skill to develop, and *communicating your process* is key to defending your work and informing your audience and collaborators.