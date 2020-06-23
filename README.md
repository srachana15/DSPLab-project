# DSPLab-project

## Speech Recognition using CNN

Team members: 
Rachana Swamy (rms816)
Shubham Panchadhar (sp5047),
Vidyarini Kanagasabapathi (vk1198)


Steps for Feature Extraction:
  1.  Convert audio to frequency domain FFT
  2.  Extract features: MFCC
  3.  Frame the signal into short frames.
  4.  For each frame calculate the periodogram estimate of the power spectrum.
  5.  Apply the mel filterbank to the power spectra, sum the energy in each filter.
  6.  Take the logarithm of all filterbank energies.
  7.  Take the DCT of the log filterbank energies.
  8.  Keep DCT coefficients 2-13, discard the rest.
 


AUDIO CLASSIFICATION RESOURCES:

https://www.youtube.com/watch?v=Z7YM-HAz-IY&list=PLhA3b2k8R3t2Ng1WW_7MiXeh1pfQJQi_P

Understanding Mel Frequency Ceptral coefficients:
http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/

Implementation:
https://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html

DCT:
http://datagenetics.com/blog/november32012/index.html
