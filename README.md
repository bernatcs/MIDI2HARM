# MIDI2HARM
Harmony chords in a new MIDI layer from MIDI or audio built in MaxMSP as a M4L device.

## Compilation
The project is configured using MaxMSP - M4L.

## For Beta tries
You have to set your pads to 1-8 MIDI signals (C#-2 to G#-2)

## Data input structure
This is an example of a major chord played by the third: 1, 4 4 7;
- The first number (1), must be the number of the line.
- The second number (4), must be the note in the chord. If I want a C chord played from C: 1, 0 4 7; / If I want a C chord played from G: 1, 7 4 7;
- The other numbers are the configuration of the chord up to 11 notes (plus the one that you are playing)

## Development
The main development steps are:

- Create an M4L device that can play fixed chords on another instrument with the SoftStep MIDI pads ✅
- The chords should be played in a middle register changing the first value of the list _[developing]_
- Easy MIDI mapping
- The chords should be play in a harmonic way with coherent voicings every time
- Recognize and analyse the harmonic lenguage that is being used
- Play chords trigered by a pedal that can work in the harmonic lenguage
- Create a easy and minimal design to the M4L
- Create a standalone app
- Maintaining the application and listening to user requests :)
