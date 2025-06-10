This repository hosts a MIDI tool that parses and removes pitchbends from files, while translating their semitonal offsets to new notes where applicable.
Applying this discretisation avoids import issues in programs that do not accept MIDI pitchbends, however it results in an overall less accurate MIDI as all microtones are lost, and note attack envelopes are repeated during transitions.
The program operates purely in the frontend, meaning it is safe, and does not require a server or separate installation of packages.

View https://thomas-xin.github.io/Midi-Discretiser/Midi.html for a publicly available page!