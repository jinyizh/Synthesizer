# Synthesizer - A sound synthesizer built using JavaFX & Maven with GUI
## Introduction
An audio synthesizer built with JavaFX and Maven. Using the graphic user interface, user can create widgets that generates different sound waves (like sine wave, square wave and linear ramp wave). It also includes filter and mixer for synthesizing the sounds. 
## Structure
Files are located in ```src/main/java/com/example/synthesizer```.
- AudioComponent (Java Interface)
  - SineWave (Java Class)
  - SquareWave (Java Class)
  - LinearRamp (Java Class)
  - VFSineWave (Java Class)
  - Mixer (Java Class)
  - Filter (Java Class)
- AudioComponentWidget (Java Interface)
  - SineWaveWidget (Java Class)
  - SquareWaveWidget (Java Class)
  - LinearRampWidget (Java Class)
  - VFSineWaveWidget (Java Class)
  - MixerWidget (Java Class)
  - FilterWidget (Java Class)
- AudioClip (Java Class)
- AudioListener (Java Class)
- SynthesizerApplication (runnable Java Class)
## Credits
Author: Jinyi Zhou. This project is based on a homework assignment in the CS6011 Computer Programming class at the University of Utah.