# Audio Pattern Detection and Repeated Phrase Counting Using MATLAB

**Type:** Group academic DSP assignment  
**Course:** EEE 4601, Islamic University of Technology (IUT)  
**Tools:** MATLAB (reported implementation)  
**Topics:** Digital Signal Processing, Audio Matching, Cross-Correlation, Peak Detection

## Project Description
This project uses MATLAB and digital signal processing techniques to detect and count repeated words or phrases in an audio recording. A short audio sample is compared with a longer recording using cross-correlation, and peaks in the similarity signal are used to estimate where the phrase occurs. The report explains preprocessing, detection, and visualization of the results.

## Reported method
1. Load the target audio and phrase template.
2. Match sample rates through resampling, if needed, and convert stereo to mono.
3. Normalize signal amplitude.
4. Compute a similarity function using MATLAB `xcorr()`.
5. Identify candidate matches using `findpeaks()` and thresholds for height, distance, and prominence.
6. Convert detected lags into timestamps and visualize the waveform and correlation response.
7. Export the detection count and timestamps to a text report.

The report documents example parameter values, including a minimum peak height of 0.1 and minimum peak prominence of 0.02. Results depend on the audio content and threshold settings.




