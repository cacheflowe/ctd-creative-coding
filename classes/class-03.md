# Class 3

## 🛠️ Languages & IDEs

- [Language differences & use-cases](https://www.quora.com/What-are-the-differences-that-exist-between-programming-languages/answer/James-Barton-129)
- [Typing](https://en.wikipedia.org/wiki/Type_system)
  - [Demo: Javascript data types & error-checking](https://editor.p5js.org/cacheflowe/sketches/RIT2lquNi)
  - [Type System for Javascript](https://dev.to/melodyleonard/type-system-for-javascript-1c1a)
  - Video: [Typing: Static vs Dynamic, Weak vs. Strong](https://www.youtube.com/watch?v=C5fr0LZLMAs)
- [Object-oriented](https://www.youtube.com/watch?v=m_MQYyJpIjg) vs [functional](https://www.youtube.com/watch?v=XGNYDjyD6G8)
  - Other [programming paradigms](https://en.wikipedia.org/wiki/Programming_paradigm)
- Languages update over time!
  - [Javascript history](https://www.educative.io/blog/javascript-versions-history)
- IDEs - what can they do for you?
  - They're built specifically for certain languages
- [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop)s
  - [Online-REPs-and-REPLs](https://joel.franusic.com/online-reps-and-repls)

## 🛠️ How does a program execute?

- [Compiling vs Interpreting](https://yesfordev.com/is-javascript-compiled-or-interpreted/)
- Basic [control flow](https://en.wikipedia.org/wiki/Control_flow) tools:
  - Functions
  - Conditionals
  - Loops
- Order of operations
  - In most languages, code executes serially by default. One operation needs to finish before the next starts.
  - *Multithreading* breaks out of the predictable order of execution and allows for more optimal performance, but at a cost of complexity

## 🛠️ Shaping our sketches

- Remapping numbers
  - User input
  - [Sliders](https://editor.p5js.org/cacheflowe/sketches/t7su_ViJ3)
  - [Random numbers](https://happycoding.io/tutorials/p5js/random)
  - Data
  - [noise()](https://twitter.com/pantrymoth/status/1557085719318990850) [basic example](https://editor.p5js.org/cacheflowe/sketches/rTspcZzcf) [advanced example](https://editor.p5js.org/cacheflowe/sketches/GemonFb9A)
  - sin() [example](https://www.hailpixel.com/articles/generative-art-simple-mathematics)
  - lerp() [example](https://editor.p5js.org/cacheflowe/sketches/GemonFb9A)
  - map()
  - modulo `%`
- Normalizing numbers
- Using `map()` - Live demo
  - Map mouse input - normalize and use for rotation
  - Map time (seconds to screen width)

## ⏱️ Time

- [Time, according to p5js](https://editor.p5js.org/cacheflowe/sketches/EdkIstnmFL):
  - `second()`, `minute()`, `hour()` use your system clock
  - Track `millis()` for custom/precise time intervals
  - `frameCount % 60`
  - `nf()`
  - `deltaTime`

## 📝 Homework:

- Read:
  - [On Meta-Design and Algorithmic Design Systems](https://runemadsen.com/blog/on-meta-design-and-algorithmic-design-systems/) by Rune Madsen
    - [MIT Media Lab's Brilliant New Logo Has 40,000 Permutations](https://www.fastcompany.com/1663378/mit-media-labs-brilliant-new-logo-has-40000-permutations-video)
    - [Cacheflowe - Nightlines](https://cacheflowe.com/art/physical/nightlines-t-shirt)
- Watch:
  - [Juice it or lose it](https://www.youtube.com/watch?v=Fy0aCDmgnxg)
    - See how animation effects give a boring game personality
- Choose a secondary tool to investigate this semester. Some suggestions:
  - Web tech: html/css/canvas/svg
  - Processing
  - openFrameworks
  - Unity or Unreal
  - Touch Designer
  - VVVV
  - Nannou
  - OpenRNDR
  - Sonic Pi
  - Chuck
- **Build a clock**
  - Textual, graphical, or both
  - Make it abstract or conceptual, not a [literal clock](https://editor.p5js.org/p5/sketches/Input:_Clock)
  - Some ideas
    - Use [millis()](https://p5js.org/reference/p5/millis/) for fine-grained time display
    - Build a countdown clock?
      - How many years do you have left to live? Use variables to calculate
      - [Doomsday Clock](https://thebulletin.org/doomsday-clock/current-time/)
      - How long before Covid is over, with variables added to the equation
    - Show multiple time zones, or use an invented time scale
    - Does IRL time of day influence the color or drawing style?
    - Add sound
    - Apply time to your favorite activity
    - Reveal the rhythm of time with shapes
    - Use Javascript for more [Date functions](https://flaviocopes.com/javascript-dates/)
    - Turn the time into another "poster" and change the content depending on the time of day
  - Inspiration
    - [Raven Kwok: Time](http://ravenkwok.com/time/)
    - [Humans since 1982: A Million Times](https://vimeo.com/channels/staffpicks/60491636)
    - [Reza Ali: Reactions](https://www.instagram.com/p/CBogs4FH4E0/)
  - Steps
    - Sketch it out on paper
    - Write some code, see if it sticks
      - Sometimes the code will lead us down different, interesting paths
    - Pivot when something isn't working and try a different approach

## 📋 Review code

- Present your posters
<!-- - What's it like working with designers?
  - Do you have a good sense of design?
  - Or can you find a designer to work with? -->
