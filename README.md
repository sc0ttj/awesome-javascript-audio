# Awesome JavaScript Audio

JavaScript tools, libraries and components for creating/managing audio, sounds and music.

## Articles

### Web Audio API

- [MSDN: Basic concepts behind Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Basic_concepts_behind_Web_Audio_API)
- [MSDN: Using the Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_Web_Audio_API)
- [MSDN: Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/)
- [MSDN: Web Audio, best practices](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Best_practices)
- [HTML5 Rocks: Scheduling Web Audio with Precision](https://www.html5rocks.com/en/tutorials/audio/scheduling/) (web audio performance)
- [HTML5 Rocks: Developing Game Audio with the Web Audio API](https://www.html5rocks.com/en/tutorials/webaudio/games/) - mixing, fixing clipping, 3d sound, ..
- [MSDN: AudioNode](https://developer.mozilla.org/en-US/docs/Web/API/AudioNode) - generic interface for representing audio (an audio source, filter, gain mixer, output, ...) 
- [MSDN: AudioBuffer](https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer) - a short audio asset residing in memory, created from an audio file
- [MSDN: OfflineAudioContext](https://developer.mozilla.org/en-US/docs/Web/API/OfflineAudioContext) - for generating sounds to buffer, fast as possible, no need to playback
- [MSDN: Controlling multiple parameters with constantSourceNode](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Controlling_multiple_parameters_with_ConstantSourceNode)
- [MSDN: Creating a simple synth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Simple_synth)
- [MSDN: Visualizations with Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Visualizations_with_Web_Audio_API)

### Web MIDI API

- [Web MIDI Examples](https://webmidi-examples.glitch.me/) - nice, short example code snippets
- [CSS Tricks: Dip your toes into hardware with Web MIDI](https://css-tricks.com/dip-your-toes-into-hardware-with-webmidi/) - covers anatomy of a MIDI signal, MIDI notes
- [Keith McMillen: Making Music in the Browser with Web MIDI API](https://www.keithmcmillen.com/blog/making-music-in-the-browser-web-midi-api/)
- [Smashing Magazine: Web MIDI API](https://www.smashingmagazine.com/2018/03/web-midi-api/)

## Web Audio API libraries

- [howler.js](https://github.com/goldfire/howler.js) - cross-browser audio library, 7kb, with multi-track, caching, falls back to HTML5 audio
- [webaudio-peaks](https://github.com/naomiaro/webaudio-peaks) - small library to get peaks from audio

## Web MIDI API libraries

These can play MIDI files, and handle MIDI input/output messages from MIDI instruments, etc:

- [mudcube/MIDI.js](https://github.com/mudcube/MIDI.js) - can play midi files using the given soundFonts
  - [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) - pre-rendered, MIDI soundfonts for use with MIDI.js 
- [jazz-soft/JZZ](https://github.com/jazz-soft/JZZ) - MIDI library for Node and Browsers
- [cwilso/WebMIDIAPIShim](https://github.com/cwilso/WebMIDIAPIShim) - popular polyfill, used by Jazzsoft, among others. [Test it here](https://cwilso.github.io/WebMIDIAPIShim/)
- [jazz-soft/WebMIDIAPIShim](https://github.com/jazz-soft/WebMIDIAPIShim) - MIDI polyfill for `navigator` in older browsers and Node
- [jazz-soft/web-midi](https://github.com/jazz-soft/web-midi) - WebMIDI API for browsers only
- [jazz-midi-electron](https://github.com/jazz-soft/jazz-midi-electron) - WebMIDI API for Electron
- [igorski/zMIDI](https://github.com/igorski/zMIDI) - small MIDI library, an easy interface to working with Web MIDI 
- [colxi/MidiParser](https://github.com/colxi/midi-parser-js) - a binary MIDI file reader for browser/Node, converts a MIDI binary file to a JSON object
- [grimmdude/MidiWriterJS](https://github.com/grimmdude/MidiWriterJS) - an API for programmatically generating multi-track MIDI files and JSON objects
- [grimmdude/MidiPlayerJS](https://github.com/grimmdude/MidiPlayerJS) - multi-track MIDI player/parser
- [hoch/spiral](https://github.com/hoch/spiral) - lightweight WebAudio/WebMIDI library

Tools for managing MIDI instruments (hardware instruments/devices):

- [webmidi](https://github.com/djipco/webmidi) - control MIDI instruments/messages with ease
- [Midi-Connector](https://github.com/nuc/Midi-Connector) - for connecting your MIDI device to `aconnect` (one of the ALSA tools)
- [tween-midi-editor](https://github.com/tuomashatakka/tween-midi-editor) - MIDI tween editor

## Music theory

Tutorials and teachers:

- [harmonizer](https://github.com/flosSoftware/harmonizer) - interactive piano that teaches harmony and rythym theory
- [play-along](https://github.com/bobbyrne01/play-along) - learn the drums using a sequencer-like UI
- [Keystack](https://github.com/danielgamage/keystack) - A web-based circular visualizer for keyboards (circle of fifths).

## Sound assets

Sounds that can be downloaded and used in your JS applications:

### SoundFonts

Instruments and sounds you can attach to MIDI notes (using the Web MIDI API):

- [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) - pre-rendered, MIDI soundfonts for use with MIDI.js 
- [soundfont-player](https://github.com/danigb/soundfont-player) - nice little library for loading and playing sound fonts

### Instrument recordings

High quality recordings of instruments, nicely organised into seprate files, in MP3, WAV or similar format. 

- ?

## Sound creation

Programmatically create notes, chords, intervals, effects, etc:

- [teoria](https://github.com/saebekassebil/teoria) - create notes, chords, scales, intervals.. get notes form intervals, and more..   
- [midiflip](https://github.com/1j01/midiflip) - transpose, flip, reverse notes, etc
- [note-parser](https://github.com/danigb/note-parser) - Given a string, obtain a hash with note properties (including midi number and frequency)
- [beep.js](https://github.com/stewdio/beep.js) - a JavaScript toolkit for building browser-based synthesizers
- [simpleTones](https://github.com/escottalexander/simpleTones.js) - create tones of a specfic note - add sawtooth, sine, triangle, etc, to modify
- [Tone.js](https://github.com/Tonejs/Tone.js) - A Web Audio framework for making interactive music in the browser
- [tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) - instrument presets for Tone.js
- Also see [LFOs](#LFOs) and [Synths](#Synths) sections.

### Low frequency oscillators ("LFOs"):

These produce sounds which oscillate between two values on a certain frequency, following a given waveform - can then be put through synths, etc.

- [TheTeapot418/LFO.js](https://github.com/TheTeapot418/LFO.js) - a simple LFO in JavaScript, includes presets: sine, triangle, square, sawtooth, noise
- [2xAA/LFO.js](https://github.com/2xAA/LFO.js) - a fork of the above
- [mohayonao/wave-tables](https://github.com/mohayonao/wave-tables) - JSON files defining various sounds/instruments as wave tables
- [diversen/wave-table-oscillators](https://github.com/diversen/wave-table-oscillators) - wrappers around the wave tables above (allows you to use them) 
- [audiojs/audio-oscillator](https://github.com/audiojs/audio-oscillator) - Generate periodic oscillation into an array/audiobuffer using a simple API
- [scijs/periodic-function](https://github.com/scijs/periodic-function) - oscillator modifiers (sawtooth, square, sine, pulse, step, interpolate, etc) as JS functions, normalized 0..1

### Pure Data (PD) patches

- [sebpiq/WebPd](https://github.com/sebpiq/WebPd) - use your [Pure Data](https://puredata.info/) [patches](https://puredata.info/community/member-downloads/patches) in Javascript

### Sound samplers:

Samplers make it easy to import, chop up, and extract parts of an audio file (usually WAV or MP3).

- ?

## Sound editing

### Sound effects/processing

- [waveform-playlist](https://github.com/naomiaro/waveform-playlist) - very nice multi-track WAV editor, similar to Audacity :)
- [wad](https://github.com/rserota/wad) - advanced processing/manipulating of sound files
- [tuna](https://github.com/Theodeus/tuna) - an audio effects library for the Web Audio API

### ADSR envelopes 

Modify a sound with more/less attack, delay, sustain, release, etc.

- [audio-contour](https://www.npmjs.com/package/audio-contour) - A 5 stage audio envelope generator.. nice UI to edit WAV forms
- [adsr-envelope](https://github.com/mohayonao/adsr-envelope) - attack, delay, sustain, release and MORE, lots of options
- [envelope-generator](https://github.com/itsjoesullivan/envelope-generator) - nice and complete, lots of options
- [adsr](https://github.com/mmckegg/adsr) - attack, delay, sustain, release envelopes

### Sound equalizers

- [GraphicalFilterEditor](https://github.com/carlosrafaelgn/GraphicalFilterEditor) - very powerful sound shaping :)
- [eAudio](https://github.com/DIDAVA/eAudio) - the "Extended HTML Audio Object" - adds an equalizier



## MIDI instruments

Frontends and UIs to load & your play your sounds.

### Drums

- ?

### Drum pads / MPC / MPD

- [completejavascript/drum-machine](https://github.com/completejavascript/drum-machine) - simple react based MPD
- [dusanpopov/Drum-machine](https://github.com/dusanpopov/Drum-machine) - an AKAI-like MPC
- [Introduction-to-Programming-Term-1-Project](https://github.com/wtznc/Introduction-to-Programming-Term-1-Project) - USB MIDI drum pad and keyboard, uses `p5`, `ZMIDI`
- [webmaeistro/drum-machine](https://github.com/webmaeistro/drum-machine) - nice, simple one, no lag, works well
- [electric-drums-pwa](https://github.com/1XWebbyX1/electric-drums-pwa) - simple, buttons at bottom, good performance
- [dburles/ssu16](https://github.com/dburles/ssu16) - very slick Akai-like MPC, with step sequencing, sample import, much more

### Guitar

- [1j01/guitar](https://github.com/1j01/guitar) - drag over the strings to play
- [ronkot/ks-guitar](https://github.com/ronkot/ks-guitar) - play chords with keyboard keys, and strum with up/down keys

### Piano

- [TomerAberbach/piano](https://github.com/TomerAberbach/piano) - very nice sounding piano, simple UI
- [qwerty-hancock](https://github.com/stuartmemo/qwerty-hancock) - simple JS piano component for larger projects, see [qwerty hancock](https://stuartmemo.com/qwerty-hancock/)
- [tri-chromatic-keyboard](https://github.com/1j01/tri-chromatic-keyboard) - nice, easy way to play piano for those who _can't_ play piano (different key layout)
- [Wscats/piano](https://github.com/Wscats/piano) - nice piano, decent sounds, can make it play for you
- [WarpPrism/AutoPiano](https://github.com/WarpPrism/AutoPiano) - feature-packed, large piano
- [iBundin/Open-Web-Piano](https://github.com/iBundin/Open-Web-Piano) - nice piano, user-friendly: supports choosing a MIDI device on load

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
- [sf2synth.js](https://github.com/logue/sf2synth.js) - sf2synth.js is WebMidiLink based SoundFont Synthesizer.
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
- [stevengoldberg/juno106](https://github.com/stevengoldberg/juno106) - Roland Juno 106 synth
- [kevin-chau/minimoog.js](https://github.com/kevin-chau/minimoog.js) - Minimoog synth

### Multi-instruments

These are more complete - they have multiple instruments.

- [midi-sounds-react](https://github.com/surikov/midi-sounds-react) - nice examples of using soundfonts, includes a simple music sequencer
- [WebMIDICon](https://github.com/dtinth/WebMIDICon) - nice collection of online instruments
- [terrible-techno](https://terrible-techno.firebaseapp.com/) - nice UI

## Complete DAWs

- [gridsound](https://github.com/gridsound/daw) - a lovely open source DAW, uses Web Audio API
- [TReactor](https://github.com/kevin-chau/TReactr) - a Traktor clone, written in React

## UI components and libraries

### React components

- [react-music](https://www.npmjs.com/package/react-music) - define sounds, effects, etc, using JSX
- [kedromelon/mdlr](https://github.com/kedromelon/mdlr) - like above, but more for sound generation (oscillators, tones, waveforms, synths) 
- [react-midi-device-provider](https://github.com/halvves/react-midi-device-provider) - simple MIDI device/messages handler for react
- [TReactor](https://github.com/kevin-chau/TReactr) - a Traktor clone, written in React

### Visual waveform generators

- [katspaugh/wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) - generate navigable waveforms
- [audio-to-svg-waveform](https://github.com/invokemedia/audio-to-svg-waveform) - simple, generates SVGs, nothing else
- [patidar-suresh/audio-waveform](https://github.com/patidar-suresh/audio-waveform) - uses HTML5 Canvas and requestAnimationFrame
- [WFPlayer](https://github.com/zhw2590582/WFPlayer) - an audio waveform generator, nice features
- [audio-oscilloscope](https://github.com/mathiasvr/audio-oscilloscope) - waveform vizualiser for HTML5 Canvas
- [waveplayer.js](https://github.com/michaeldzjap/waveplayer.js) - mp3 player that produces wavforms
- [chrisweb/waveform-visualizer](https://github.com/chrisweb/waveform-visualizer) - waveform generator

### Audio visualization

- [vudio.js](https://github.com/margox/vudio.js) - very nice bouncing bars, can place or align at top, bottom, left, right or center
- [pts.js](https://ptsjs.org/) - a powerful creative coding and visualization library

### Other UI 

- [webaudio-controls](https://github.com/g200kg/webaudio-controls) - web components aimed at VST instruments, DAWs, etc
- [abcjs](https://github.com/paulrosen/abcjs) - for rendering music notation
- [williamfields/nofft.js](https://github.com/williamfields/nofft.js) - Javascript library for creating MIDI-responsive visuals
- [nexus-js/ui](https://github.com/nexus-js/ui) - very nice UI toolkit for web based MIDI instrument [UI components](https://nexus-js.github.io/ui/) (used by nofft, above)



