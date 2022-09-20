# Class 9

## 📋 Review code

* Present your webcam/hardware sketches

## 🛠️ Project recap

* [Interphase](https://cacheflowe.com/code/installation/interphase)
* [#dancelab](https://cacheflowe.com/code/installation/dancelab-dam) @ DAM

## 🛠️ Open Source

* Freely-available source code!
* Different kinds of [licenses](https://opensource.org/licenses)
  * These determine how you can (or can't) legally use the code in your projects. Make sure you're allowed to use the code for your commercial (or non-commercial) purposes.
* [How does it happen?](http://opensource.guide/)
  * OS development [funding models](https://mkaz.blog/misc/open-souce-funding-models/)
  * Personal projects
  * Internal tools that become their own library
  * [The struggles of an open source maintainer](http://antirez.com/news/129)
* Libraries & frameworks
  * [What is the difference between a framework and a library?](https://www.youtube.com/watch?v=D_MO9vIRBcA)?
  * Processing is the framework, but has a [libraries](https://processing.org/reference/libraries/) manager built in
* Package (library) managers
  * Why?
    * Quick & easy
    * Dependency management
    * One source for the latest tools
  * Downsides
    * Security
    * Large download size
    * Versioning/dependencies can break over time
  * Different languages have different package managers
    * Processing: library manager inside IDE
    * p5js: N/A - you include remote javascript files or upload them
    * Javascript: Node.js (npm)
    * Java: Maven
    * Ruby: Bundler
    * Python: pip
    * OS X: Homebrew
    * Windows: Chocolatey

## 🛠️ Audio

* Samples vs. Synthesis
  * Samples
    * [p5.SoundFile](https://p5js.org/reference/#/p5.SoundFile)
    * [Sample playback via button click](https://p5js.org/examples/sound-sound-effect.html)
    * [Sound playback rate](https://p5js.org/examples/sound-playback-rate.html)
  * Synthesis
    * [p5.Oscillator](https://p5js.org/reference/#/p5.Oscillator)
    * [Oscillator Frequency](https://p5js.org/examples/sound-oscillator-frequency.html)
    * [Note Envelope](https://p5js.org/examples/sound-note-envelope.html)
* Making music
  * Basic building blocks
    * Data & timing to create "[sequencer](https://axelfuhrmann.com/step-sequencer)" patterns
    * Notes, chords & scales
    * Changing parameters over time
  * Tools/examples
    * [WebAudio Weekly](https://www.webaudioweekly.com/)
    * [Chrome Music Lab](https://musiclab.chromeexperiments.com/)
    * [WebMIDI](https://www.onlinemusictools.com/webmiditest/)
    * [DrumBot](https://twitter.com/notwaldorf/status/1201599495244537858)
    * [ZzFX](https://github.com/KilledByAPixel/ZzFX)
    * [meSing.js](http://usdivad.com/mesing/)
    * [Beet.js](http://zya.github.io/beet.js/)
    * [Blip.js](http://jshanley.github.io/blip/)
    * [Zupiter](https://pointersgonewild.com/2019/10/06/zupiter-a-web-based-modular-synthesizer/)
    * [PatternSketch](https://patternsketch.com/)
* [Scales](https://p5js.org/examples/hello-p5-song.html) & [frequencies](https://www.translatorscafe.com/unit-converter/en-US/calculator/note-frequency/)
  * [Algorithmic Music Composition](https://junshern.github.io/algorithmic-music-tutorial/) - interactive tutorial in p5js
* Audio input
  * [FFT analysis](https://editor.p5js.org/p5/sketches/Sound:_FFT_Spectrum)
  * [Amplitude analysis](https://p5js.org/examples/sound-measuring-amplitude.html)
  * [More demos](https://therewasaguy.github.io/p5-music-viz/)
    * [Realtime pitch detection](https://therewasaguy.github.io/p5-music-viz/demos/06c_autoCorrelation_PitchTrack/)
* Other tools for creating music
  * Processing libraries:
    * [Beads](http://www.beadsproject.net/)
    * [Minim](http://code.compartmental.net/tools/minim/)
  * [WebAudio](http://cacheflowe.github.io/audio-hax/)
  * [Max](https://cycling74.com/products/max/)
  * [Tone.js](https://tonejs.github.io/examples/)
  * [Sonic PI](http://sonic-pi.net/)
  * [ORCA](https://github.com/hundredrabbits/Orca)
  * [ChucK](http://chuck.cs.princeton.edu/)
  * [Supercollider](http://supercollider.github.io/)
  * [Alda](https://alda.io/)
  * [Extempore](https://extemporelang.github.io/)
  * [Overtone](http://overtone.github.io/)
  * [TidalCycles](https://tidalcycles.org/)
  * [EarSketch](http://earsketch.gatech.edu/landing/)
  * [Aubio](https://aubio.org/)
  * [Sound eXchange](http://sox.sourceforge.net/) (cli conversion tool, like ffmpeg but for audio files)
  * [JUCE](https://juce.com/)
  * [VCV Rack](https://vcvrack.com/Prototype) ([+ plugin docs](https://vcvrack.com/manual/PluginDevelopmentTutorial))
  * [Ableton Live Connection Kit](https://www.ableton.com/en/packs/connection-kit/)
* Inspiration
  * [generative.fm](https://generative.fm/)
  * [Blob opera](https://artsandculture.google.com/experiment/blob-opera/AAHWrq360NcGbw)

## 📝 Homework:

* Read:
  * [Introduction to Generative Music](https://medium.com/@alexbainter/introduction-to-generative-music-91e00e4dba11)
  * [Algorithmic Music Composition](https://junshern.github.io/algorithmic-music-tutorial/) - interactive tutorial in p5js
  * [Algorithmic Music @ Wikipedia](http://en.wikipedia.org/wiki/Algorithmic_music)
  * Advanced articles (optional, just for kicks)
    * [What Is the Web Audio API?](https://teropa.info/blog/2016/08/19/what-is-the-web-audio-api.html)
    * [JavaScript Systems Music](https://teropa.info/blog/2016/07/28/javascript-systems-music.html)
    * [Generating music in the waveform domain](https://benanne.github.io/2020/03/24/audio-generation.html)
    * [Advanced audio signal processing books](https://ccrma.stanford.edu/~jos/) by Julius Orion Smith III
* Watch & listen:
  * "The Code Creative" [Web Audio API video tutorials](https://www.youtube.com/playlist?list=PLMPgoZdlPumc_llMSynz5BqT8dTwr5sZ2)
  * [George E. Lewis: Why Do We Want Our Computers to Improvise?](https://www.youtube.com/watch?v=wDP8FsjyCaA)
  * [The Ballad of the Psychotropic Robots](https://www.youtube.com/watch?v=nhq6wzgFEXc)
  * [Ryoji Ikeda | data.path](https://www.soundart.zone/ryoji-ikeda-data-path/)
  * [Autechre: Sign review – electronic masters soar and fall in negative space](https://www.theguardian.com/music/2020/oct/16/autechre-sign-review-warp)
    * [Autechre Worked in Isolation for Decades. Now It’s Unintentionally Timely.](https://www.nytimes.com/2020/10/13/arts/music/autechre-sign-interview.html)
  * [William Fields - Fields OS](https://williamfields.bandcamp.com/album/fieldsos)
    * "FieldsOS is 100% algorithmic music. The probabilities, conditions, and constraints were configured in advance. The output was recorded and this is the result. No curation or editing was done."
* Build something with audio
  * Ideas:
    * Write a program that plays a sound along with a graphical element
    * Build an interactive or self-playing instrument
    * Visualize microphone or audio file analysis
    * Synthesize some sounds
    * Build a drum pad/machine like [Bongo.cat](https://bongo.cat/)
  * Resources:
    * Free audio files
      * [https://freesound.org/](https://freesound.org/)
      * [https://sampleswap.org/](https://sampleswap.org/)
    * Wave editors (record & edit your own audio files)
      * [Audacity](https://www.audacityteam.org/) (desktop app)
      * [AudioMass](https://audiomass.co/)
