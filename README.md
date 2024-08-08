<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Audio Signal Processing using MATLAB</h1>
    
   <h2>Project Overview</h2>
    <p>This project demonstrates various techniques in audio signal processing using MATLAB. The primary focus is on analyzing, filtering, and transforming audio signals to understand their spectral properties and bandwidth characteristics.</p>

  <h3>Key Features:</h3>
   <ul>
        <li><strong>Audio Signal Analysis</strong>: Reading and analyzing audio signals to extract useful information such as the sampling rate and spectral characteristics.</li>
        <li><strong>Spectrogram Generation</strong>: Visualizing the frequency content of the audio signal over time using spectrograms.</li>
        <li><strong>Power Spectral Density (PSD)</strong>: Estimating and plotting the power spectral density of the audio signal.</li>
        <li><strong>Fourier Transform</strong>: Applying the Fast Fourier Transform (FFT) to convert the signal from the time domain to the frequency domain.</li>
        <li><strong>Lowpass Filtering</strong>: Designing and applying a lowpass filter to remove high-frequency components from the audio signal.</li>
        <li><strong>Highpass Filtering</strong>: Designing and applying a highpass filter to remove low-frequency components from the audio signal.</li>
        <li><strong>Filtered Signal Analysis</strong>: Analyzing the spectrogram and bandwidth of the filtered signals.</li>
        <li><strong>Audio Playback and Saving</strong>: Playing back the original and filtered audio signals and saving the filtered signals as new audio files.</li>
    </ul>

   <h2>Project Structure</h2>
    <pre>
audio-signal-processing-matlab/
│
├── BUMMER.WAV              # Input audio file
├── handel.mat              # Preloaded audio data from MATLAB
├── audio_signal_processing.m  # Main MATLAB script
└── README.md               # Project documentation
    </pre>

   <h2>Key Functions</h2>
   <ul>
        <li><code>audioread</code>: Reads audio files into MATLAB.</li>
        <li><code>sound</code>: Plays audio signals.</li>
        <li><code>fft</code>: Computes the Fast Fourier Transform.</li>
        <li><code>specgram</code>: Generates spectrograms.</li>
        <li><code>obw</code>: Calculates the occupied bandwidth.</li>
        <li><code>fdesign.lowpass</code>: Designs lowpass filters.</li>
        <li><code>fdesign.highpass</code>: Designs highpass filters.</li>
    </ul>


   <h2>Contact</h2>
    <p>For any inquiries, please contact <a href="mailto:das201706@gmail.com">yEmail</a>.</p>

</body>
</html>
