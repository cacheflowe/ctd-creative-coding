# Class 5

## 🛠️ Debugging

![Debugging meme](../images/debugging.png)

If you've got an AI coding assistant set up, it's a great addition to your debugging toolkit too - but see [Coding and learning with AI](../docs/learning-with-ai.md) for how to lean on it without atrophying your own debugging skills.

### Resources

![Documentation meme](../images/rtfm-he-man.png)

* [p5js Debugging article](https://p5js.org/tutorials/field-guide-to-debugging/)
* [Errors in JavaScript](https://www.youtube.com/watch?v=O0EHKBi7iXU)
* ["Expert Software Developers' Approach to Error"](https://www.youtube.com/watch?v=UNMF5AS4SLg)
* [67 Weird Debugging Tricks Your Browser Doesn't Want You to Know](https://alan.norbauer.com/articles/browser-debugging-tricks)

### What to do when something doesn't work

![Extra bracket meme](../images/roses-are-red.jpg)

* Does your IDE point out any syntax problems?
* Is there an error message in the console?
  * Is there a "[stack trace](https://en.wikipedia.org/wiki/Stack_trace)"?
* Check your syntax
* Check for typos
* Can you make a more basic version of the code do something?
* Double-check the documentation
* Do some Googling - has someone else had this problem?
* Get help from ChatGPT or Copilot
* Take a step back - is something obvious being overlooked?
  * Are we editing the right file?
  * Are we observing the right server (e.g., localhost vs production)?
  * Has something changed that seemed insignificant at the time?
  * Have you tried restarting your development environment or server and clearing any caches?

### General debugging

![Typo/error meme](../images/typo-error.jpg)

* Reference errors (is your code pointing to the right thing?)
* `console.log()` / `println()`
* Debuggers - [live demo](http://localhost/haxademic.js/demo/#three-scene)

### Graphical debugging

"Why aren't things drawing the way I expect them to?"

* It's hard, because there as less-obvious ways to identify a problem
* If something isn't displaying, can you make a simpler version?
* Add a "debug view"
  * In GLSL (shaders), there's no textual logging or output, so developers will draw various textures and stages of pixel operations to the screen to decipher what might be happening
  * [#debugviewart](https://www.instagram.com/explore/tags/debugviewart/)

## 🛠️ Software Design (How software works, and how to write better code)

![We thought it would be easy](../images/thought-it-would-be-easy.png)

### How does a program execute?

- Entry point (main function)
- [Compiling vs Interpreting](https://dev.to/robiulhr/is-javascript-compiled-or-interpreted-language-l20)
- Basic [control flow](https://en.wikipedia.org/wiki/Control_flow) tools:
  - Functions
  - Conditionals (branching logic)
  - Loops
  - [Control flow diagram](../images/control-flow.png)
- Order of operations
  - In most languages, code executes serially by default. One operation needs to finish before the next starts.
  - *Multithreading* breaks out of the predictable order of execution and allows for more optimal performance, but at a cost of complexity

### General advice for cleaner, better code
- Practice! Solving the same type of problem over time allows you to experiment with different approaches
- Ask for feedback from your peers or mentors (or AI)
- Refactor and clean up your own code once it's working. Can you find ways to make it simpler, cleaner, more reliable or efficient?
- Study common coding techniques. What are people in the industry talking & writing about?
  - Watch online lessons and talks from conferences
  - Read blog posts
  - Follow developers on social media

### Strategies

Use [Design patterns](https://medium.com/educative/the-7-most-important-software-design-patterns-d60e546afb0e)
- It takes experience to know which might be best in a given situation, so start trying them out!

Look for opportunities to [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) (Don't Repeat Yourself) up your code
- [Video: What is DRY code?](https://www.youtube.com/watch?v=HwTcjWtDAfc)
- [Article: "Is Your Code DRY or WET?"](https://dzone.com/articles/is-your-code-dry-or-wet)

SOLID principles
- [SOLID principles](https://stackoverflow.blog/2021/11/01/why-solid-principles-are-still-the-foundation-for-modern-software-architecture/)
- [The SOLID Principles in Pictures](https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898)
- [Applying SOLID principles in React](https://konstantinlebedev.com/solid-in-react/)

Defensive programming

Try [Refactoring](https://refactoring.guru/) your code for better organization and code clarity
- Readability (see below)
- Comments
- Indentation
- OOP (classes) - [Example sketch](https://editor.p5js.org/cacheflowe/sketches/488Fdh1O1)
- Separate files
- Build scripts
- Package managers
- es6 imports

![Example of readability over brevity](../images/clarity-over-brevity.jpg)

### How to build anything

- ![Follow the engineering design process](../images/engineering-design-process.jfif)
- Break the problem down into smaller components
  - Plan for each component of the problem, then follow the process above
  - Writing and testing isolated code is a great way to solve these smaller, focused components
  - Build a larger plan to connect the smaller pieces - this is software design
  - Use a project management or task-tracking tool to keep track of your progress
- Write ugly code, then clean it up once it works
  - Don't over-engineer it until it's working
- Ask someone for help/advice!
- What happens when you hit a wall?
  - Sleep on it
  - Go for a walk
  - Use [a](https://en.wikipedia.org/wiki/Rubber_duck_debugging) [duck](https://rubberduckdebugging.com/)
  - Try a different approach or reduce your ambition this time around. You'll figure it out with persistence!
- Build your toolkit as you find solutions
  - [Haxademic](https://github.com/cacheflowe/haxademic/) is one of mine

## 📝 Homework

Read

- [So you want to build a generator](http://galaxykate0.tumblr.com/post/139774965871/so-you-want-to-build-a-generator) by Kate Compton
- [Shepherding Random Numbers](https://inconvergent.net/2016/shepherding-random-numbers/) by Inconvergent
- [Emergence and Generative Art](https://www.amygoodchild.com/blog/emergence) by Amy Goodchild
- [Randomness in the Composition of Artwork](https://tylerxhobbs.com/essays/2014/randomness-in-the-composition-of-artwork) by Tyler Hobbs
- [Probability Distributions for Algorithmic Artists](https://tylerxhobbs.com/essays/2014/probability-distributions-for-algorithmic-artists) by Tyler Hobbs
- [What makes generative art hard?](https://bendotk.com/writing/what-makes-generative-art-hard) by Ben Kovach

**Build a "generator"**

- Shapes
- Some ideas
  - [Basic example](https://editor.p5js.org/cacheflowe/sketches/JytAPkkLQ0)
  - Generate an environment
  - Or a character
  - Or a pattern
  - Or a particle system
  - Animate your generated visuals
  - Add sound!

Inspiration

- [Manolo](https://www.behance.net/manoloide) - [code](https://github.com/manoloide/AllSketchs)
- [Dave Bollinger](https://www.flickr.com/photos/davebollinger/)
- [Saskia Freeke: Patterns](http://sasj.nl/)
- [Andreas Gysin: Bots](https://www.instagram.com/p/B9KGXmNByRa/)
- [Everest Pipkin: Mirror Lake](https://everestpipkin.itch.io/mirrorlake)
- [Lolo Armdz](https://www.instagram.com/p/Bo9XS81HomN/)
- [Amanda Cifaldi: Tiny Spires](https://botsin.space/@tinyspires)
- [Cacheflowe: Branchers](https://www.threads.net/@cacheflowe/post/Cu0sWaTAX7R)
- [Kjetl Golid](https://www.instagram.com/p/B1FUsgSANMz/)
- [Frederik Vanhoutte](https://www.instagram.com/p/B9scpU8HgXY/)
- [Dmitri Cherniak](https://www.instagram.com/p/CDzmKONnAlj/)
- [Caleb Ogg](https://www.instagram.com/p/B_YjBSYnMn1/)
- fxhash
  - [KilledByAPixel](https://www.fxhash.xyz/u/KilledByAPixel)
  - [flight404](https://www.fxhash.xyz/u/flight404)
  - [toxi](https://www.fxhash.xyz/u/toxi)
  - [https://www.fxhash.xyz/generative/slug/panta-rei](https://www.fxhash.xyz/generative/slug/panta-rei)

## 📋 Review code

- Present your looping animations
