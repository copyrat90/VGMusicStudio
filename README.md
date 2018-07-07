# Kermalis's GBA Music Studio

A tool that is designed to be a Sappy replacement and also support different game engines.

![Preview](https://i.imgur.com/MOBHq03.gif)

----
# Some Advantages Over Sappy:
* Pause button & song position changing
* You can play the in-game instruments with a MIDI-in keyboard
* You can view and edit track events
* You can import MIDI files without having to convert them yourself
* You can save the voice tables to SF2 soundfont files
* You can save songs to ASM S files
* The UI scales to the desired window size
* You can see representation of notes being played
* It is not intimidating to use
* Support for multiple song tables
* Support for "Mario & Luigi: Superstar Saga"

----
# To Do:
## M4A / MP2K Engine

* Add reverb DSP effect
* Add reverse playback
* Add SquareWave sweeping
* Add "note off with noise" for SquareWaves
* Repeat command
* Nested PATT (3 is the maximum)
* Fix ADSR on PSG instruments
* Find out why some instruments sound strange \[Example: Mario Kart Snow Land drum\]
* Songtable finder
* Support pret dissassembly projects
* Running status in song disassembler
* Add the restriction back to tempo
* MIDI saving - preview the MIDI with the Sequencer class
* MIDI saving - UI with saving options, such as remapping

## Mario & Luigi: Superstar Saga Engine
* Properly implement "free notes"
* Volume command
* Panpot command
* Voice tables

## General
* Add playing playlist from Games.yaml and fading out after a configurable amount of loops
* Maybe a nice waveform
* Exception handling for invalid config
* Add keyboard shortcuts to the UI
* Let on-screen piano play notes or interact with MIDI keyboard
* Remove "private set" in config and add saving of config
* Fix UI checkboxes breaking randomly
* Songtable length in config and expander
* Default remap voice
* Offset for event you're editing
* Once an event is edited, call SongPlayer.SetPosition() to update the song
* Put the event parameter as text in the parameter name label, so there is reference to the original value or in MODT/Note's cases, text representation
* Double-clicking an event sets the song's position to that tick
* Buttons in the taskbar like with most music players
* Edit "Pok�mon Emerald" & "Mario & Luigi: Superstar Saga" playlists
* Tempo numerical (it fits)
* Fix events past a goto counting as higher ticks
* Detachable piano
* Help dialog that explains the commands for each format
* Think about if keeping all songs in memory (and their voice tables in them) was *actually* a good idea

----
# Special Thanks To:
* Ipatix
* tuku473
* Bregalad
* mimi
* Jesse (jelle)
* SomeShrug