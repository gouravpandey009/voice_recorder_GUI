# voice_recorder_GUI

Recording voice using Python can be achieved with the help of the `sounddevice` and `SoundFile` modules. This guide will walk you through the process of recording voice and saving it as a file.

### Modules Required

1. **Sounddevice**: This module provides bindings for the PortAudio library and offers convenience functions to play and record NumPy arrays containing audio signals. Install it using the following command:

    ```
    pip install sounddevice
    ```

2. **SoundFile**: SoundFile can read and write sound files. Install it using the following command:

    ```
    pip install SoundFile
    ```

### Approach

1. Import the necessary modules.
2. Set the desired frequency and duration for recording.
3. Record voice data into a NumPy array using the `rec()` function.
4. Store the recorded data into a file using `soundfile.write()`.

### Sample Code


This code will record voice for the specified duration (in seconds) and save it as a WAV file named `recorded_voice.wav`. Adjust the `frequency` and `duration` variables as needed.
