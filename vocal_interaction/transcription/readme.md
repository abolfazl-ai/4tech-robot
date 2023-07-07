## It's recommended to follow these steps:

- Identify the spoken language using [Whisper](https://github.com/openai/whisper) model
- Chose the best transcription service from [Google speech recognition](https://cloud.google.com/speech-to-text/),
  [Microsoft Azure speech](https://azure.microsoft.com/en-us/products/cognitive-services/speech-to-text/),
  [Whisper](https://github.com/openai/whisper), [Vosk](https://github.com/alphacep/vosk-api/) or any other service
- Check if the robot is online, use the preferred online service. It's recommended to use
  [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) library because it's simple and supports many
  online and offline services
- If the robot is offline, transcribe the audio using [Whisper models](https://huggingface.co/openai) or
  [Vosk models](https://alphacephei.com/vosk/models)
- return the transcribed text and identified language
