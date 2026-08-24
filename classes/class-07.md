# Class 7

## 🛠️ Audio

🎤 **Case study**: [Interphase](https://cacheflowe.com/code/installation/interphase) - a deeper look at building an interactive music generator with physical lighting

Justin's examples of different audio uses in creative code

* [Interphase](https://cacheflowe.com/code/installation/interphase)
  * [Interphase preview](https://cacheflowe.com/images/code/installation/cacheflowe-interphase-jenise-jensen-wave-8195.jpg)
  * Interactive music generator software w/physical lighting
    * [New iterations](https://cacheflowe.com/code/lab/c-a-c-h-e)
* [#dancelab](https://cacheflowe.com/code/installation/dancelab-dam) @ DAM
  * All choreography & computer-generated visuals were synced to the tempo of the music
* [Bauhouse](https://cacheflowe.com/art/digital/bauhouse) 
  * Graphics respond to audio triggering (built w/Interphase music engine)
* [Feetboxin](https://cacheflowe.com/code/lab/feetboxin)
  * Piezo (impact) sensors send MIDI signals that trigger audio, but also are turn into DMX signals to trigger the lights
* [HaxVisual](https://cacheflowe.com/code/lab/haxvisual-audioreactive-vj-software)
  * Incoming audio signal is analysed and used to draw audio-reactive images
* [Obsidian](https://cacheflowe.com/art/digital/obsidian)
  * Looping animation was matched exactly to the length of the looping audio track
* [Webcam sonification](https://www.instagram.com/p/CIytqIxljZG/)
  * Using pixel data to translate into a looping sound wave

Samples vs. Synthesis

* Samples
  * [p5.SoundFile](https://p5js.org/reference/p5.sound/p5.SoundFile/)
  * [Sample playback via button click](https://editor.p5js.org/p5/sketches/Sound:_Sound_Effect)
  * [Sound playback rate](https://editor.p5js.org/p5/sketches/Sound:_Manipulate_Sound)
* Synthesis
  * [p5.Oscillator](https://p5js.org/reference/p5.sound/p5.Oscillator/)
  * [Oscillator Frequency](https://editor.p5js.org/p5/sketches/Sound:_Oscillator_Waveform)
  * [Note Envelope](https://editor.p5js.org/p5/sketches/Sound:_Note_Envelope)

Making music

* Basic building blocks
  * Data & timing to create "[sequencer](https://step-sequencer.afuh.dev/)" patterns ([author info](https://afuh.dev/step-sequencer/))
  * Notes, chords & scales
    * [Scales](https://editor.p5js.org/p5/sketches/Hello_P5:_song) & [frequencies](https://www.translatorscafe.com/unit-converter/en-US/calculator/note-frequency/)
  * [Algorithmic Music Composition](https://junshern.github.io/algorithmic-music-tutorial/) - interactive tutorial in p5js
  * [Generative Music AI Course](https://www.youtube.com/playlist?list=PL-wATfeyAMNqAPjwGT3ikEz3gMo23pl-D) - YouTube series
  * Changing parameters over time
* Tools
  * [WebAudio](https://webaudioapi.com/samples/)
    * [Tone.js](https://tonejs.github.io/examples/)
    * [WebAudio Weekly](https://www.webaudioweekly.com/)
  * [WebMIDI](https://www.onlinemusictools.com/webmiditest/)
    * [Justin's example MIDI sketch](https://editor.p5js.org/cacheflowe/sketches/xuGYeJnZY)
    * [Justin's example MIDI sketch 2](https://editor.p5js.org/cacheflowe/sketches/iFMtaetat)
* Examples
  * [All possible 8 step hihat rhythms](https://bsky.app/profile/piterpasma.nl/post/3luxjya5iyc2h)
  * [Chrome Music Lab](https://musiclab.chromeexperiments.com/)
  * [Blob Opera](https://artsandculture.google.com/experiment/blob-opera/AAHWrq360NcGbw)
  * [generative.fm](https://generative.fm/)
  * [Felix Turner](https://twitter.com/felixturner/status/1569821623133556737)
* More examples of web-based music tools
  * [DrumBot](https://twitter.com/notwaldorf/status/1201599495244537858)
  * [ZzFX](https://github.com/KilledByAPixel/ZzFX)
  * [meSing.js](http://usdivad.com/mesing/)
  * [Beet.js](http://zya.github.io/beet.js/)
  * [Blip.js](http://jshanley.github.io/blip/)
  * [Zupiter](https://pointersgonewild.com/2019/10/06/zupiter-a-web-based-modular-synthesizer/)
  * [PatternSketch](https://patternsketch.com/)


Audio input

* [FFT analysis](https://editor.p5js.org/p5/sketches/Sound:_FFT_Spectrum) from microphone input
* [Amplitude analysis](https://editor.p5js.org/p5/sketches/Sound:_Amplitude_Analysis) from sound file
* [More demos](https://therewasaguy.github.io/p5-music-viz/)
  * Specific example: [Realtime pitch detection](https://therewasaguy.github.io/p5-music-viz/demos/06c_autoCorrelation_PitchTrack/)

Other tools for creating music with code

* Live coding
  * [Sonic PI](http://sonic-pi.net/)
  * [TidalCycles](https://tidalcycles.org/)
    * [Strudel](https://strudel.cc/workshop/getting-started/) (web-based TidalCycles environment)
  * [ORCA](https://github.com/hundredrabbits/Orca)
  * [ChucK](http://chuck.cs.princeton.edu/)
  * [Gibber](https://gibber.cc/)
  * [Overtone](http://overtone.github.io/)
  * [Alda](https://alda.io/)
  * [Extempore](https://extemporelang.github.io/)
  * [EarSketch](http://earsketch.gatech.edu/landing/)
* [Max](https://cycling74.com/products/max/)
* [Supercollider](http://supercollider.github.io/)
* [Aubio](https://aubio.org/)
* [Sound eXchange](http://sox.sourceforge.net/) (cli conversion tool, like ffmpeg but for audio files)
* [JUCE](https://juce.com/)
* [VCV Rack](https://vcvrack.com/Prototype) ([+ plugin docs](https://vcvrack.com/manual/PluginDevelopmentTutorial))
* [Ableton Live Connection Kit](https://www.ableton.com/en/packs/connection-kit/)


## 📝 Homework:

Read:

* [Introduction to Generative Music](https://medium.com/@alexbainter/introduction-to-generative-music-91e00e4dba11)
* [Algorithmic Music Composition](https://junshern.github.io/algorithmic-music-tutorial/) - interactive tutorial in p5js
* [Algorithmic Music @ Wikipedia](http://en.wikipedia.org/wiki/Algorithmic_music)
* [Live Coding Handbook](https://livecodingbook.toplap.org/)
* Advanced articles (optional, just for kicks)
  * [Katie Fenn – Around the wwworld: Web MIDI, Web AUDIO and what the web does best – All Day Hey! 2025](https://www.youtube.com/watch?v=9R3hIvfRLMY)
  * [What Is the Web Audio API?](https://teropa.info/blog/2016/08/19/what-is-the-web-audio-api.html)
  * [JavaScript Systems Music](https://teropa.info/blog/2016/07/28/javascript-systems-music.html)
  * [Generating music in the waveform domain](https://benanne.github.io/2020/03/24/audio-generation.html)
  * [Advanced audio signal processing books](https://ccrma.stanford.edu/~jos/) by Julius Orion Smith III

Watch & listen:

* [Making Music with CODE?! (With DJ_Dave and Sam Aaron)](https://www.youtube.com/watch?v=vuSZQnkOB_Y)
* Tutorials
  * "The Code Creative" [Web Audio API video tutorials](https://www.youtube.com/playlist?list=PLMPgoZdlPumc_llMSynz5BqT8dTwr5sZ2)
  * [Luisa Pereira's classes](https://www.luisapereira.net/teaching/)
* Conceptual interviews
  * [Computer Music (Synthesizers, Synclavier) News Report w/Stanley Jordan (1986)](https://www.youtube.com/watch?v=duMStO826W0)
  * [George E. Lewis: Why Do We Want Our Computers to Improvise?](https://www.youtube.com/watch?v=wDP8FsjyCaA)
  * [Autechre: Sign review – electronic masters soar and fall in negative space](https://www.theguardian.com/music/2020/oct/16/autechre-sign-review-warp)
    * [Autechre Worked in Isolation for Decades. Now It's Unintentionally Timely.](https://www.nytimes.com/2020/10/13/arts/music/autechre-sign-interview.html)
* Art examples
  * [Simon Russell - Beat Visualization](https://vimeo.com/687076688)
  * [The Ballad of the Psychotropic Robots](https://www.youtube.com/watch?v=nhq6wzgFEXc)
  * [Ryoji Ikeda | data.path](https://www.soundart.zone/ryoji-ikeda-data-path/)
  * [William Fields - Fields OS](https://williamfields.bandcamp.com/album/fieldsos)
    * "FieldsOS is 100% algorithmic music. The probabilities, conditions, and constraints were configured in advance. The output was recorded and this is the result. No curation or editing was done."

**Build something with audio**

* Ideas:
  * Write a program that plays a sound file along with a graphical element
  * Build an interactive or self-playing instrument
  * Visualize microphone or audio file analysis
  * Synthesize some sounds with oscillators
  * Build a drum pad/machine like [Bongo.cat](https://bongo.cat/)
  * Use MIDI
* Resources: Free audio files
  * [freesound.org](https://freesound.org/)
  * [sampleswap.org](https://sampleswap.org/)
* Resources: Wave editors (record & edit your own audio files)
  * [Audacity (Tenacity)](https://tenacityaudio.org/) (free desktop app)
  * [Wavacity](https://wavacity.com/) (free browser-based app)
  * [AudioMass](https://audiomass.co/) (free browser-based app)

## 📋 Review code

* Present your data visualizations
