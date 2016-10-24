# grainfields
8 voice granular synthesizer for monome 128 grids

### Getting started

Before launching grainfields make sure that your grid is connected. At the lower right corner of the app go to "audio & osc setup" and choose your device in the serialosc dropdown (should auto detect).

Set your audio settings and enable audio. 

### 8 rows / 8 voices

Drag and drop audio samples onto the waveform display of the individual voices, or simply record directly into the buffer from any given input.

### Lemur interface 

Control individual voices directly in the application or via the included Lemur interface (requires Lemur on iPad). 

Install the interface on iPad ('monome_grainfields.jzml' in the project folder) and make sure to provide the correct port and host settings for incoming and outgoing OSC.

### Grain parameters

Control the grain density, base pitch and deviation, duration, loop rate, amplitude, envelope slope, and stereo spread of each voice. Additional parameters include:

- "speed" (sets the speed of moving between grain positions in miliseconds)
- "fade" (sets the fade in / out time when activating / deactivating a voice)
- "rec length" (sets the length of recording into the buffer)

### Global transport & pattern recorder

Start / stop transport by pressing the space bar. The transport needs to be activated to record pattern gestures. 

Set the desired length of the pattern loop in bars (default=2). 

### Recording into buffer

When recording an input source into a buffer the buffer will autosave the recording into the project folder (located inside the "media" folder).

### Master presets

Saving a preset (shift>click on a slot) will store all current parameter settings in each voice as well as the file path of buffer contents.

### Credits
Patch created by Kasper Fangel Skov 2016
