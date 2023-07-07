## It's recommended to follow these steps:

- Prepare data using microphone and your own voice in two categories: wake_word and background. Save the recordings in
  wav format in separate directories.
- Preprocess the data using [Librosa](https://librosa.org/) MFCC
- Train a TensorFlow model using [this tutorial](https://www.tensorflow.org/tutorials/audio/simple_audio)
- Test the model and save it
- Run a service in background and listen to the audio through mic. Use the trained model to detect the wake word and
  call the call-back function when the wake word is detected 
