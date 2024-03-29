# Separation of Musical Instruments using Audio Samples

## Aim 

The objective is to train the neural networks on audio samples, using tools like Fourier Transform, to separate musical instruments from other sounds. The models will then perform the algorithm of matching waveforms on the test set to evaluate the algorithm.

## Task Breakdown (First run) 

- Dataset - [MUSDB18](https://zenodo.org/record/1117372#.ZBSU6HZBzEY)
- Fourier transform - signal domain transformation.  
  - LiBROSA (pip install librosa). Embedded with almost all of the necessary features for handling .wav files (Loading, visualizing, playing etc) 
  - Scipy (pip install scipy) - for mathematical analysis (in our case fft). Although I still prefer using pytorch.fft since integration processing would be faster. 
  - Adding spectrogram to our analysis can be a salient features. (Task - look up how to code a spectrogram in python) 
- Major task - [Understanding and implementing ASR](https://github.com/flashlight/flashlight/tree/main/flashlight/app/asr)  
- Tutorials to follow -  
  + [AudioDL](https://towardsdatascience.com/audio-deep-learning-made-simple-sound-classification-step-by-step-cebc936bbe5) 
  + [PyTorch](https://pytorch.org/tutorials/intermediate/speech_command_classification_with_torchaudio_tutorial.html) 
- Model deployment - Either using [streamlit](https://towardsdatascience.com/deploying-ml-models-using-streamlit-5d6212453bdd) or [flask](https://www.geeksforgeeks.org/deploy-machine-learning-model-using-flask/) (I prefer the first)  

