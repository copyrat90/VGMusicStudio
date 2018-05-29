# Kermalis's GBA Music Studio

A tool that is designed to be an updated Sappy.

![Preview](https://i.imgur.com/fsfxud4.gif)

## Some Advantages Over Sappy
* Pause button
* You can play the in-game instruments with a MIDI-in keyboard
* You can save the voice tables to a SF2 soundfont file
* The UI scales to the desired window size
* It is not intimidating to use

## To Do (No particular order)

* Drums are a bit funky sometimes, I have to check how they work again
* Figure out GB instrument frequency scale
* Add reverse playback
* Add pitch & volume modulation
* Add SquareWave sweeping
* Add KEYSH
* Add "note off with noise" for SquareWaves
* Add playing playlist from Games.yaml and fading out after a configurable amount of loops
* Fix songs not releasing before dying
* Fix audible velocity abruption when notes are overridden by others (noticeable when the DirectSound limit is 5)
* Maybe a nice waveform
* Finish integrating SF2 writing
* MIDI saving of songs
* Songtable finder
* Give instruments a defined color and have the bars show those colors, along with the keys on the piano
* Exception handling for invalid config
* Mute checkboxes next to tracks, along with another that indicates the piano will reflect the notes