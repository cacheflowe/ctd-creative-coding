# Class 3

## 🛠️ Programming Languages

[Language differences & use-cases](https://www.quora.com/What-are-the-differences-that-exist-between-programming-languages/answer/James-Barton-129)

[Typing](https://en.wikipedia.org/wiki/Type_system)
- > In computer programming, a **type system** is a logical system comprising a set of rules that assigns a property called a type (for example, **integer**, **floating point**, **string**) to every term (a word, phrase, or other set of symbols). Usually the terms are various language constructs of a computer program, such as **variables**, **expressions**, **functions**, or **modules**. A type system dictates the operations that can be performed on a term. For variables, the type system determines the allowed values of that term.<br><br>Type systems formalize and enforce the otherwise implicit categories the programmer uses for algebraic data types, data structures, or other data types, such as "string", "array of float", "function returning boolean".
- [Type System for Javascript](https://dev.to/melodyleonard/type-system-for-javascript-1c1a): 
  - > JavaScript is a dynamically-typed language. What this means is that it performs type checking at runtime. <br><br>Take for instance a language like java or C++ which is a statically-typed language. Type checking in such language is performed at compile time. This is very useful as it warns the programmer of all type errors before the code executes successfully. This way, programmers are subjected to [fewer errors].
  - > JavaScript is a weakly typed language. It recognizes different data types (numbers, strings, etc.), but doesn't use them too strictly, trying to convert data when it seems reasonable. [Many] expressions that don't work in other languages work perfectly well in JavaScript. Try to perform any arithmetic operation (except addition) with strings or another data type (except when both operands are numbers or strings consisting only of numbers). You will see that they always work and return NaN, which makes sense.<br><br>In strongly typed languages, adding a number to a string won't work. ([Source](https://code-basics.com/languages/javascript/lessons/data-types-weak-typing))
- Video: [Typing: Static vs Dynamic, Weak vs. Strong](https://www.youtube.com/watch?v=C5fr0LZLMAs)

Programming paradigms:
- [Object-oriented](https://www.youtube.com/watch?v=m_MQYyJpIjg) (imperative)
- [Functional](https://www.youtube.com/watch?v=XGNYDjyD6G8) (declarative)
  - [Unleash JavaScript's Potential with Functional Programming](https://janhesters.com/blog/unleash-javascripts-potential-with-functional-programming)
- [And others](https://en.wikipedia.org/wiki/Programming_paradigm)

Languages update over time:
- [Javascript history](https://www.educative.io/blog/javascript-versions-history)

## 🛠️ IDEs

- IDEs - what can they do for you?
  - An IDE (Integrated Development Environment) lets you write, compile, and run code all in one place
  - They're built specifically for certain languages and have tools to help you write code faster and with fewer errors
  - They can be customized with plugins and themes
- [REPLs](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop)
  - [Online-REPs-and-REPLs](https://joel.franusic.com/Online-REPs-and-REPLs)

## 🛠️ How does a program execute?

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

## 🛠️ Shaping our sketches

- Remapping numbers
  - User input
  - [Sliders](https://editor.p5js.org/cacheflowe/sketches/t7su_ViJ3)
  - [Random numbers](https://happycoding.io/tutorials/p5js/random)
  - Data
  - [noise()](https://p5js.org/reference/p5/noise/)
    - [example: noise grid offset](https://editor.p5js.org/cacheflowe/sketches/rTspcZzcf) 
    - [example: noise circles](https://editor.p5js.org/cacheflowe/sketches/MsjQH_kPi)
    - [example: textured noise mesh](https://editor.p5js.org/cacheflowe/sketches/XVQjjklv2)
  - sin() [example](https://editor.p5js.org/cacheflowe/sketches/WpJ24V4vq)
    - [Making generative art with simple mathematics](https://www.hailpixel.com/articles/generative-art-simple-mathematics)
    - TD: `lfo`/`pattern`/`function` CHOPs
  - lerp() [example](https://editor.p5js.org/cacheflowe/sketches/GemonFb9A)
  - map() [example](https://editor.p5js.org/cacheflowe/sketches/v88Rfyxhi)
  - modulo `%` [example](https://editor.p5js.org/cacheflowe/sketches/O9JM1Lp0n)
- Normalizing numbers
- Using `map()` - Live demo
  - Map mouse input - normalize and use for rotation
  - Map time (seconds to screen width)

## ⏱️ Time

- [Time, according to p5js](https://editor.p5js.org/cacheflowe/sketches/EdkIstnmFL):
  - `second()`, `minute()`, `hour()` uses your system clock
  - Track `millis()` for custom/precise time intervals
  - `frameCount % 60`
  - `nf()`
  - `deltaTime`
- Time according to TouchDesigner (live demo)

## 🛠️ Animation

* Exercises:
  * Intro to [basic movement](https://editor.p5js.org/p5/sketches/Motion:_Bounce)
  * And more [examples/exercises](https://creative-coding.decontextualize.com/changes-over-time/)
* Real-time coding vs scripting or event-based or reactive environments
  * `noLoop()` option in p5.js

## 📝 Homework:

Read:

- [On Meta-Design and Algorithmic Design Systems](https://runemadsen.com/blog/on-meta-design-and-algorithmic-design-systems/) by Rune Madsen
  - [MIT Media Lab's Brilliant New Logo Has 40,000 Permutations](https://www.fastcompany.com/1663378/mit-media-labs-brilliant-new-logo-has-40000-permutations-video)
  - [Cacheflowe - Nightlines](https://cacheflowe.com/art/physical/nightlines-t-shirt)

Watch:

- [Secrets of Game Feel and Juice](https://www.youtube.com/watch?v=216_5nu4aVQ)
- [Juice it or lose it](https://www.youtube.com/watch?v=Fy0aCDmgnxg)
  - See how animation effects can give an otherwise boring game lots of personality

Choose a secondary tool to investigate this semester. Some suggestions:

- Web tech: html/css/canvas/svg
  - THREE.js
  - React / react-three-fiber
- Unity or Unreal
- TouchDesigner
- VVVV
- Processing
- openFrameworks
- Nannou
- OpenRNDR
- Sonic Pi
- Tidal Cycles or Strudel
- Chuck

**Build a clock**

- Textual, graphical, or both
- Make it abstract or conceptual, not a [literal clock](https://editor.p5js.org/p5/sketches/Input:_Clock)
- Some ideas
  - Use [millis()](https://p5js.org/reference/p5/millis/) for fine-grained time display
  - Build a countdown clock?
    - How long until you graduate, or other big life milestones?
    - How many years do you have left to live? Use variables to calculate
    - [Doomsday Clock](https://thebulletin.org/doomsday-clock/current-time/)
  - Show multiple time zones, or use an invented time scale
  - Does IRL time of day influence the color or drawing style?
  - Add sound
  - Apply time to your favorite activity
  - Reveal the rhythm of time with shapes
  - Use Javascript for more [Date functions](https://flaviocopes.com/javascript-dates/)
  - Turn the time into another "poster" and change the content depending on the time of day
- Inspiration
  - [Raven Kwok: Time](http://ravenkwok.com/time/)
  - [Humans since 1982: A Million Times](https://vimeo.com/60491636)
  - [Reza Ali: Reactions](https://www.instagram.com/p/CBogs4FH4E0/)
- Steps
  - Sketch it out on paper
  - Write some code, see if it sticks
    - Sometimes the code will lead us down different, interesting paths
  - Pivot when something isn't working and try a different approach

## 📋 Review code

- Present your posters

