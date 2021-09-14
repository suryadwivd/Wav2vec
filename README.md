# Housing data extraction and training

Speech to Text conversion using [Wav2vec](https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/).

Install dependencies from 'requirements.txt'.
Store the audio to be processed in the same directory named as 'sample_audio.wav'.
Depending on the speaker in the audio, change the parameters 'min_silence_len' and 'silence_thresh'.
The text from the recognized audio will be stored in 'text.txt' file after the audio is processed in the notebook.