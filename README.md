# Awesome JavaScript Audio

JavaScript tools, libraries and components for creating/managing audio, sounds and music.

## Articles and videos

### Music theory

- [Let's learn about waveforms](https://pudding.cool/2018/02/waveforms/) - really nice interactives to teach waveforms by Pudding.cool [source code](https://github.com/joshwcomeau/waveforms)
- [The Physics of Music](https://pages.mtu.edu/~suits/Physicsofmusic.html) by Michigen Tech
- [JS Dynamic Audio Synth Tutorial](https://keithwhor.com/music/) - make a [synth piano keyboard](https://mrcoles.com/piano/) from scratch, covers lots of theory 
- [Principles of Sound Synthesis](http://www.acoustics.salford.ac.uk/acoustics_info/sound_synthesis/) - or, why synths can't do guitars
- [Drum patterns and exercises](https://www.ethanhein.com/wp/my-nyu-masters-thesis/drum-patterns-and-exercises/) - master thesis by Ethan Hein, with nice circle system 
  - [Video: Play With Your Rhythm - Drum Patterns](https://www.youtube.com/watch?v=tm2BgO1VaRY) - nice explanation of various drums patterns 
  - [Video: Play With Your Rhythm - Build a beat](https://www.youtube.com/watch?v=kpSudIoepgY) - follow up to the above video
  - [Doc: Play With Your Rhythm](https://docs.google.com/spreadsheets/d/19_3BxUMy3uy1Gb0V8Wc-TcG7q16Amfn6e8QVw4-HuD0/edit#gid=0) - spreadsheet showing notations for all patterns
- [solfej.io/chords](https://www.solfej.io/chords) - search any chord to hear it, and see how to play on various instruments
- [solfej.io/scales](https://www.solfej.io/chords) - search any scales to hear it, and see how to play, and which chords are in the scale

### Web Audio API

- [MSDN: Basic concepts behind Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Basic_concepts_behind_Web_Audio_API)
- [MSDN: Using the Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_Web_Audio_API)
- [MSDN: Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/)
- [MSDN: Web Audio, best practices](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Best_practices)
- [HTML5 Rocks: Scheduling Web Audio with Precision](https://www.html5rocks.com/en/tutorials/audio/scheduling/) (web audio performance)
- [HTML5 Rocks: Developing Game Audio with the Web Audio API](https://www.html5rocks.com/en/tutorials/webaudio/games/) - mixing, fixing clipping, 3d sound, ..
- [MSDN: AudioNode](https://developer.mozilla.org/en-US/docs/Web/API/AudioNode) - generic interface for representing audio (an audio source, filter, gain mixer, output, ...) 
- [MSDN: AudioBuffer](https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer) - a short audio asset residing in memory, created from an audio file
- [MSDN: AudioBufferSourceNode](https://developer.mozilla.org/en-US/docs/Web/API/AudioBufferSourceNode) - for audio with stringent timing/accuracy requirements
- [MSDN: OfflineAudioContext](https://developer.mozilla.org/en-US/docs/Web/API/OfflineAudioContext) - for generating sounds to buffer, fast as possible, no need to playback
- [MSDN: Controlling multiple parameters with constantSourceNode](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Controlling_multiple_parameters_with_ConstantSourceNode)
- [MSDN: Creating a simple synth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Simple_synth)
- [Drum Sounds in Web Audio](https://dev.opera.com/articles/drum-sounds-webaudio/) - creating drums sounds using the Web Audio API
- [MSDN: Visualizations with Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Visualizations_with_Web_Audio_API)
- [Visualizations with Audio API and D3](https://blog.scottlogic.com/2016/01/06/audio-api-with-d3.html) - tutorial on music visualisation with D3, [demo](https://wpferg.uk/MusicVisualisation/)
- [Music frequency visualizer with D3](https://www.bignerdranch.com/blog/music-visualization-with-d3-js/) - nice short guide, with [repo](https://github.com/bignerdranch/music-frequency-d3) and [demo](https://bignerdranch.github.io/music-frequency-d3/)
- [Visualising Sound with D3](https://medium.com/better-programming/visualizing-sound-with-d3-and-web-audio-api-435ffea88f30) - covers and demos various different visualisations

### Web MIDI API

- [Web MIDI Examples](https://webmidi-examples.glitch.me/) - nice, short example code snippets
- [CSS Tricks: Dip your toes into hardware with Web MIDI](https://css-tricks.com/dip-your-toes-into-hardware-with-webmidi/) - covers anatomy of a MIDI signal, MIDI notes
- [Keith McMillen: Making Music in the Browser with Web MIDI API](https://www.keithmcmillen.com/blog/making-music-in-the-browser-web-midi-api/)
- [Smashing Magazine: Web MIDI API](https://www.smashingmagazine.com/2018/03/web-midi-api/)

## Books

- [Web Audio API](https://webaudioapi.com/book/Web_Audio_API_Boris_Smus_html/toc.html) - for JS developers, game devs, etc. Written by Boris Smus.
- [Programming Electronic Music in Pure Data (PD)](http://www.pd-tutorial.com/english/index.html)

## Libraries: Web Audio API

- [howler.js](https://github.com/goldfire/howler.js) - cross-browser audio library, 7kb, with multi-track, caching, falls back to HTML5 audio
- [webaudio-peaks](https://github.com/naomiaro/webaudio-peaks) - small library to get peaks from audio
- [kittykatattack/sound.js](https://github.com/kittykatattack/sound.js) - micro library to load, generate and play sounds
- [notthetup/smoothfade](https://github.com/notthetup/smoothfade) - smooth fade between AudioNodes
- [scriptify/sountility](https://github.com/scriptify/sountility) - includes many small packages for adding, mixing, toggling effects on AudioNodes

## Libraries: Web MIDI API

- [cwilso/WebMIDIAPIShim](https://github.com/cwilso/WebMIDIAPIShim) - popular polyfill, used by Jazzsoft, among others. [Test it here](https://cwilso.github.io/WebMIDIAPIShim/)
- [jazz-soft/WebMIDIAPIShim](https://github.com/jazz-soft/WebMIDIAPIShim) - MIDI polyfill for `navigator` in older browsers and Node

These can play MIDI files, and handle MIDI input/output messages from MIDI instruments, etc:

- [mudcube/MIDI.js](https://github.com/mudcube/MIDI.js) - can play midi files using the given soundFonts
  - [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) - pre-rendered, MIDI soundfonts for use with MIDI.js 
- [jazz-soft/JZZ](https://github.com/jazz-soft/JZZ) - MIDI library for Node and Browsers
- [jazz-soft/web-midi](https://github.com/jazz-soft/web-midi) - WebMIDI API for browsers only
- [jazz-midi-electron](https://github.com/jazz-soft/jazz-midi-electron) - WebMIDI API for Electron
- [igorski/zMIDI](https://github.com/igorski/zMIDI) - small MIDI library, an easy interface to working with Web MIDI 
- [colxi/MidiParser](https://github.com/colxi/midi-parser-js) - a binary MIDI file reader for browser/Node, converts a MIDI binary file to a JSON object
- [grimmdude/MidiWriterJS](https://github.com/grimmdude/MidiWriterJS) - an API for programmatically generating multi-track MIDI files and JSON objects
- [grimmdude/MidiPlayerJS](https://github.com/grimmdude/MidiPlayerJS) - multi-track MIDI player/parser
- [hoch/spiral](https://github.com/hoch/spiral) - lightweight WebAudio/WebMIDI library
- [dingram/jsmidgen](https://github.com/dingram/jsmidgen) - generate MIDI files from javascript
- [node-easymidi](https://github.com/dinchak/node-easymidi) - a wrapper around [node-midi](https://github.com/justinlatimer/node-midi) to make things easier

These are tools for managing MIDI instruments (hardware instruments/devices):

- [webmidi](https://github.com/djipco/webmidi) - control MIDI instruments/messages with ease
- [Midi-Connector](https://github.com/nuc/Midi-Connector) - for connecting your MIDI device to `aconnect` (one of the ALSA tools)
- [tween-midi-editor](https://github.com/tuomashatakka/tween-midi-editor) - MIDI tween editor
- [AndrejHronco/midi-ports](https://github.com/AndrejHronco/midi-ports) - small library to manage attached MIDI ports and devices
- [jazz-soft/JZZ-midi-Gear](https://github.com/jazz-soft/JZZ-midi-Gear) - get info about your MIDI device

## Developer tools

- [google/audion](https://github.com/google/audion) - adds a new tab to Chrome DevTools with a node editor to view your AudioNodes 
- [Pure Data](https://puredata.info/) - develop your own synths and patches

## Music theory

Tutorials and teachers:

- [harmonizer](https://github.com/flosSoftware/harmonizer) - interactive piano that teaches harmony and rhythm theory
- [play-along](https://github.com/bobbyrne01/play-along) - learn the drums using a sequencer-like UI
- [Keystack](https://github.com/danielgamage/keystack) - A web-based circular visualizer for keyboards (circle of fifths).
- [funklet](http://funklet.com/) - learn famous drum beats using an interactive sequencer
- [scribbletune/johann](https://scribbletune.github.io/johann/) - Generate chord & scale charts to practice - for guitar, piano and PC keyboard ([repo](https://github.com/scribbletune/johann))

## Sound assets

Sounds that can be downloaded and used in your JS applications:

### SoundFonts

Instruments and sounds you can attach to MIDI notes (using the Web MIDI API):

- [ryanwhite04/soundfonts](https://github.com/ryanwhite04/soundfonts) - includes [lots of instruments](https://ryanwhite04.github.io/soundfonts/), in mp3 and ogg
- [surikov/webaudiofont](https://github.com/surikov/webaudiofont) - use full GM set of musical instruments to play MIDI and single sounds or effects
- [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) - pre-rendered, MIDI soundfonts for use with MIDI.js 
- [soundfont-player](https://github.com/danigb/soundfont-player) - nice little library for loading and playing sound fonts
- [danigb/sampler.js](https://github.com/danigb/sampler.js) - simple sampler, defines instruments as JSON, with base64 mp3s in them
- [sccherry/soundfont](https://github.com/sccherry/soundfont) - soundfont piano player, uses 'FluidR3_GM', 'MusyngKite', 'FatBoy' ([demo](https://stevecherry.net/soundfont/#index))
- [letoribo/percussion-soundfonts](https://github.com/letoribo/percussion-soundfonts) - soundfonts for JZZ.synth.MIDI.js
- [timbre_soundfonts.js](https://github.com/skratchdot/timbre.soundfont.js) - soundfonts for [timbre.js](https://github.com/mohayonao/timbre.js/)
- [PatrickWolleb/SoundFontJS](https://github.com/PatrickWolleb/SoundFontJS) - Node JS CLI for creating MIDI.JS ready sound fonts
- [colinbdclark/sf2-parser](https://github.com/colinbdclark/sf2-parser) - a SoundFont 2 parser, extracted from [sf2synth.js](https://github.com/gree/sf2synth.js)
- [montyanderson/soundfont-parser](https://github.com/montyanderson/soundfont-parser) - soundfont parser that gets the detais/contents of .sfz files
- [midijssf-from-sf2-pmb](https://github.com/mk-pmb/midijssf-from-sf2-pmb) - utilities for converting soundfonts to MIDI.js format
- [skratchdot/soundfont2mp3](https://github.com/skratchdot/soundfont2mp3) - a command line tool for extracting single note mp3s from soundfont files

### Instrument recordings

High quality recordings of instruments, nicely organised into seprate files, in MP3, WAV or similar format. 

- ?

## Sound creation

Programmatically create notes, chords, intervals, effects, etc:

- [Tone.js](https://github.com/Tonejs/Tone.js) - A Web Audio framework for making interactive music in the browser
- [tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) - instrument presets for Tone.js
- [teoria](https://github.com/saebekassebil/teoria) - create notes, chords, scales, intervals.. get notes form intervals, and more..   
- [octavian](https://github.com/stevekinney/octavian) - utilities for reasoning about musical notes, frequencies, and intervals 
- [Flocking](https://github.com/colinbdclark/Flocking) - declaratively create sounds, synths, effects, etc, as JSON objects, supports mouse/trackpad
- [scribbletune](https://scribbletune.com/) - generate chord progressions, scales, beats, save as MIDI clips, with [a teacher app](https://github.com/scribbletune/johann) and [sampler](https://github.com/scribbletune/sampler)
- [btwael/zazate.js](https://github.com/btwael/zazate.js) - make notes, tones, scales, chords, harmonies.. loads of functions
- [timbre.js](https://github.com/mohayonao/timbre.js/) - JavaScript library for objective sound programming (archived)
- [midiflip](https://github.com/1j01/midiflip) - transpose, flip, reverse notes, etc
- [note-parser](https://github.com/danigb/note-parser) - Given a string, obtain a hash with note properties (including midi number and frequency)
- [simpleTones](https://github.com/escottalexander/simpleTones.js) - create tones of a specfic note - add sawtooth, sine, triangle, etc, to modify
- [beep.js](https://github.com/stewdio/beep.js) - a JavaScript toolkit for building browser-based synthesizers
- Also see [LFOs](#LFOs) and [Synths](#Synths) sections.

### Low frequency oscillators ("LFOs"):

These produce sounds which oscillate between two values on a low frequency, following a given waveform. LFOs are usually used to create effects like pitch wobble, tremelo, and wah-wah-wah stuff. These effect are then applied to notes, synths or instruments.

- [TheTeapot418/LFO.js](https://github.com/TheTeapot418/LFO.js) - a simple LFO in JavaScript, includes presets: sine, triangle, square, sawtooth, noise
- [2xAA/LFO.js](https://github.com/2xAA/LFO.js) - a fork of the above
- [mohayonao/wave-tables](https://github.com/mohayonao/wave-tables) - JSON files defining various sounds/instruments as wave tables
- [diversen/wave-table-oscillators](https://github.com/diversen/wave-table-oscillators) - wrappers around the wave tables above (allows you to use them) 
- [audiojs/audio-oscillator](https://github.com/audiojs/audio-oscillator) - Generate periodic oscillation into an array/audiobuffer using a simple API
- [scijs/periodic-function](https://github.com/scijs/periodic-function) - oscillator modifiers (sawtooth, square, sine, pulse, step, interpolate, etc) as JS functions, normalized 0..1

### Pure Data (PD) patches

- [sebpiq/WebPd](https://github.com/sebpiq/WebPd) - use your [Pure Data](https://puredata.info/) [patches](https://puredata.info/community/member-downloads/patches) in Javascript

## Sound editing

### Sound effects/processing

- [alemangui/pizzicato](https://github.com/alemangui/pizzicato) - excellent sound shaping effects, [nice demos](https://alemangui.github.io/pizzicato/) showing guitar sounds
- [wad](https://github.com/rserota/wad) - advanced processing/manipulating of sound files
- [tuna](https://github.com/Theodeus/tuna) - an audio effects library for the Web Audio API
- [scriptify/Chnl](https://github.com/scriptify/Chnl) - makes it easy to attach lots of effects to a single AudioNode of any kind

### Sound samplers:

Samplers make it easy to import, chop up, and extract parts of an audio file (usually WAV or MP3).

- [waveform-playlist](https://github.com/naomiaro/waveform-playlist) - very nice multi-track WAV editor, similar to Audacity :)
- [hya-wave](https://wav.hya.io/#/fx) - nice online WAV editor

### ADSR envelopes 

Modify a sound with more/less attack, delay, sustain, release, etc.

- [audio-contour](https://www.npmjs.com/package/audio-contour) - A 5 stage audio envelope generator.. nice UI to edit WAV forms
- [adsr-envelope](https://github.com/mohayonao/adsr-envelope) - attack, delay, sustain, release and MORE, lots of options
- [envelope-generator](https://github.com/itsjoesullivan/envelope-generator) - nice and complete, lots of options
- [adsr](https://github.com/mmckegg/adsr) - attack, delay, sustain, release envelopes

### Sound equalizers

- [GraphicalFilterEditor](https://github.com/carlosrafaelgn/GraphicalFilterEditor) - very powerful sound shaping :)
- [eAudio](https://github.com/DIDAVA/eAudio) - the "Extended HTML Audio Object" - adds an equalizier

### Vocoders

For Editing and adding effects to vocals.

- [cwilso/vocoder](https://github.com/cwilso/vocoder) - a 28-band vocoder - a "robotic voice" processor

## MIDI instruments

Frontends and UIs to load & your play your sounds.

### Drum pads / MPC / MPD

- [completejavascript/drum-machine](https://github.com/completejavascript/drum-machine) - simple react based MPD
- [dusanpopov/Drum-machine](https://github.com/dusanpopov/Drum-machine) - an AKAI-like MPC
- [Introduction-to-Programming-Term-1-Project](https://github.com/wtznc/Introduction-to-Programming-Term-1-Project) - USB MIDI drum pad and keyboard, uses `p5`, `ZMIDI`
- [webmaeistro/drum-machine](https://github.com/webmaeistro/drum-machine) - nice, simple one, no lag, works well
- [electric-drums-pwa](https://github.com/1XWebbyX1/electric-drums-pwa) - simple, buttons at bottom, good performance
- [dburles/ssu16](https://github.com/dburles/ssu16) - very slick Akai-like MPC, with step sequencing, sample import, much more
- [cwilso/MIDIDrums](https://github.com/cwilso/MIDIDrums) - MIDI version of Shiny Drum Machine 

### Guitar

- [1j01/guitar](https://github.com/1j01/guitar) - drag over the strings to play
- [ronkot/ks-guitar](https://github.com/ronkot/ks-guitar) - play chords with keyboard keys, and strum with up/down keys
- [vitaliy-bobrov/js-rocks](https://github.com/vitaliy-bobrov/js-rocks) - lots of nice electric guitar effects, amps and cabinets

### Piano

- [midi-with-node](https://github.com/Pomax/midi-with-node) - a web based GUI & NodeJS backend that can register as a MIDI device in your DAW
- [TomerAberbach/piano](https://github.com/TomerAberbach/piano) - very nice sounding piano, simple UI
- [qwerty-hancock](https://github.com/stuartmemo/qwerty-hancock) - simple JS piano component for larger projects, see [qwerty hancock](https://stuartmemo.com/qwerty-hancock/)
- [tri-chromatic-keyboard](https://github.com/1j01/tri-chromatic-keyboard) - nice, easy way to play piano for those who _can't_ play piano (different key layout)
- [Wscats/piano](https://github.com/Wscats/piano) - nice piano, decent sounds, can make it play for you
- [WarpPrism/AutoPiano](https://github.com/WarpPrism/AutoPiano) - feature-packed, large piano
- [iBundin/Open-Web-Piano](https://github.com/iBundin/Open-Web-Piano) - nice piano, user-friendly: supports choosing a MIDI device on load
- [noodle-doodle](https://github.com/Pomax/noodle-doodle) - a nice piano roll, [demo here](https://pomax.github.io/noodle-doodle/) 

### Sequencers & Trackers

Use (often) grid-based, stepped/looping sequencer UIs to generate beats, riffs, bass-lines, loops and so on.

- [efflux-tracker](https://github.com/igorski/efflux-tracker) - browser based music tracker ([here](https://www.igorski.nl/application/efflux/)) driving a modular synth environment with MIDI support
- [web-drum-sequencer](https://github.com/stufreen/web-drum-sequencer) - A drum machine and sequencer built with the Web Audio API, React, and Redux
- [da-beat-sequencer](https://github.com/juniorheptachords/da-beat-sequencer) - lightweight MIDI and audio sequencer
- [drum-sequencer](https://github.com/bweave/drum-sequencer) - lightweight sequencer, simple UI
- [drum-machine](https://github.com/GK-Hynes/drum-machine) - simple sequencer, based on React
- [hatsumatsu/108](https://github.com/hatsumatsu/108) - a slick, minimalist circular beat sequencer
- [tinysynth](https://github.com/n1k0/tinysynth) - a nice little sequencer, easy to use, nice UI, generate random tracks
- [nicolas-van/sonant-x-live](https://github.com/nicolas-van/sonant-x-live) - piano keyboard, filters, synth, sequencer, uses [sonant-x](https://github.com/nicolas-van/sonant-x)
- [andrefcasimiro/midikrew](https://github.com/andrefcasimiro/midikrew) - full fledged music sequencer, built with React

### Synths

Generate and edit your own sounds, voices and sound effects.

- [jssynth](https://github.com/jstrait/jssynth) - powerful synth and sequencer
- [sf2synth.js](https://github.com/logue/sf2synth.js) - a WebMidiLink based synthesizer with SoundFont support
- [okaybenji/submono](https://github.com/okaybenji/submono) - small mono-voice (monophonic) synth, define sounds as JS objects
- [okaybenji/subpoly](https://github.com/okaybenji/subpoly) - small multi-voice (polyphonic) synth, define sounds as JS objects
- [nicolas-van/sonant-x](https://github.com/nicolas-van/sonant-x) - lightweight synth library
- [ronkot/ks-guitar-synth](https://github.com/ronkot/ks-guitar-synth) - guitair synth, using [Karplus-Strong](http://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis) algorithm. See [ks-guitar](https://github.com/ronkot/ks-guitar) for UI.
- [webaudio-tinysynth](https://github.com/g200kg/webaudio-tinysynth) - webaudio-tinysynth is a small synthesizer written in JavaScript with GM like timbre map
- [diversen/pluggable-synth](https://github.com/diversen/pluggable-synth) - small synth, lightweight piano UI, supports MIDI or keyboard
- [Tinusw/webAudioSynth](https://github.com/Tinusw/webAudioSynth) - has 2 oscillators with XY pads, and a piano keyboard
- [hundredrabbits/Marabu](https://github.com/hundredrabbits/Marabu) - powerful synth, with GUI
- [errozero/poly-synth](https://github.com/errozero/poly-synth) - fully-fledged synth, with GUI, presets, etc
- [ZulfadhliM/web-synth](https://github.com/ZulfadhliM/web-synth) - basic synth with LFO modulation and XY pad, React-based
- [stevengoldberg/juno106](https://github.com/stevengoldberg/juno106) - a Roland Juno 106 synth
- [kevin-chau/minimoog.js](https://github.com/kevin-chau/minimoog.js) - a Minimoog synth
- [francoisgeorgy/BS2-Web](https://github.com/francoisgeorgy/BS2-Web) - a very polished web interface for the BassStation II synth
- [d3-synth](https://roadtolarissa.com/synth/) - synth sounds, with circular tracker UI. Very nice, clean code

### Multi-instruments

These are more complete - they have multiple instruments.

- [midi-sounds-react](https://github.com/surikov/midi-sounds-react) - nice examples of using soundfonts, includes a simple music sequencer
- [WebMIDICon](https://github.com/dtinth/WebMIDICon) - nice collection of online instruments
- [terrible-techno](https://terrible-techno.firebaseapp.com/) - nice UI

## Complete DAWs

A "DAW" is a digital audio workstation - an all-round music production app

- [gridsound](https://github.com/gridsound/daw) - a lovely open source DAW, uses Web Audio API
- [audionodes](https://audionodes.com/online/) - very user-friendly, node editor based DAW (not open source)
- [TReactor](https://github.com/kevin-chau/TReactr) - a Traktor clone, written in React
- [XinDaw](https://github.com/dotgreg/XinDaw) - a multiscreen Web-based DAW designed for audio&video live performances (Tone.js/React/Meteor)
- [zrythm](https://github.com/zrythm/zrythm) - requires isgn up. A highly automated and intuitive DAW
- [audiotool](https://www.audiotool.com/) - requires sign up. Lots of tools and features, also available as a Chrome extension
- [soundation](https://soundation.com/) - requires sign up. Sleek looking DAW, looks similar to Non-DAW

## UI components and libraries

### React components

- [react-music](https://www.npmjs.com/package/react-music) - define sounds, effects, etc, using JSX
- [kedromelon/mdlr](https://github.com/kedromelon/mdlr) - like above, but more for sound generation (oscillators, tones, waveforms, synths) 
- [react-midi-device-provider](https://github.com/halvves/react-midi-device-provider) - simple MIDI device/messages handler for react
- [TReactor](https://github.com/kevin-chau/TReactr) - a Traktor clone, written in React
- [midi-sounds-react](https://www.npmjs.com/package/midi-sounds-react) - 1500 instruments

### Visual waveform generators

- [bbc/peaks.js](https://github.com/bbc/peaks.js) - UI component for interacting with waveforms
- [katspaugh/wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) - generate navigable waveforms
- [audio-to-svg-waveform](https://github.com/invokemedia/audio-to-svg-waveform) - simple, generates SVGs, nothing else
- [patidar-suresh/audio-waveform](https://github.com/patidar-suresh/audio-waveform) - uses HTML5 Canvas and requestAnimationFrame
- [WFPlayer](https://github.com/zhw2590582/WFPlayer) - an audio waveform generator, nice features
- [audio-oscilloscope](https://github.com/mathiasvr/audio-oscilloscope) - waveform vizualiser for HTML5 Canvas
- [waveplayer.js](https://github.com/michaeldzjap/waveplayer.js) - mp3 player that produces wavforms
- [chrisweb/waveform-visualizer](https://github.com/chrisweb/waveform-visualizer) - waveform generator

### Node editors

Also known as "graph editors".

Link your sounds, effects, inputs & outputs together with a drag and drop interface:

- [cwilso/WebAudio](https://github.com/cwilso/WebAudio) - awesome, easy-to-use node editor, with [demo](https://webaudioplayground.appspot.com)
- [tai2/webaudiocomposer](https://github.com/tai2/webaudiocomposer) - audio node-editor with a patch-based UI, like Quartz composer
- [dataflow-webaudio](https://github.com/forresto/dataflow-webaudio) - Dataflow graph editor + Web Audio API - [demo](https://forresto.github.io/dataflow-webaudio/)

### Audio visualization

- [vudio.js](https://github.com/margox/vudio.js) - very nice bouncing bars, can place or align at top, bottom, left, right or center
- [pts.js](https://ptsjs.org/) - a powerful creative coding and visualization library
- [kelvinau/circular-audio-wave](https://github.com/kelvinau/circular-audio-wave) - circular audio waves powered by E-charts
- [party-mode](https://github.com/preziotte/party-mode) - a d3 based visualizer with lots of options

### Other UI 

- [webaudio-controls](https://github.com/g200kg/webaudio-controls) - web components aimed at VST instruments, DAWs, etc
- [abcjs](https://github.com/paulrosen/abcjs) - for rendering music notation
- [williamfields/nofft.js](https://github.com/williamfields/nofft.js) - Javascript library for creating MIDI-responsive visuals
- [nexus-js/ui](https://github.com/nexus-js/ui) - very nice UI toolkit for web based MIDI instrument [UI components](https://nexus-js.github.io/ui/) (used by nofft, above)
- [ISNIT0/webaudio-generator](https://github.com/ISNIT0/webaudio-generator) - a UI for generating Web Audio API code


