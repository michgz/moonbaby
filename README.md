# moonbaby
A project to create a song listing of a child's toy from China. It is a hanging mobile, sold under several brands including "Moonbaby" and "Princess". It comes with a remote control for song selection and has 400 instrumental songs, as
well as a handful of audio recordings that can be played. It has a motor to rotate the mobile, but that motor was disabled as part of this project in order to extend battery life. The unit also has a rotating image that it can project onto the ceiling.

The following steps are proposed:
- Record the full playback
- Transcribe to MIDI-equivalent form using librosa library and similar tools
- Break into the 400 individual tracks
- Re-synthesise each song using more standard instrumentation
- Run each one through an online AI-based music recognition service
- Tabulate results

For copyright reasons, recordings and MIDI-equivalent data from the unit won't be made public on Github. However, scripts used for the analysis as well as the final song listing will be published here. 
