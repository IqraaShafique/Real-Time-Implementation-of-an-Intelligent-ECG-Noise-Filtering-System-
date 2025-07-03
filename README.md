# Real-Time-Implementation-of-an-Intelligent-ECG-Noise-Filtering-System-
This report includes the design and implementation of a real-time ECG noise filtering system 
utilizing MATLAB's static (IIR elliptic) and adaptive (LMS-based) filtering approaches. The MIT-BIH 
Arrhythmia Database provided the raw ECG signal, which was purposefully tainted with typical 
noise sources such baseline wander (0.3 Hz), powerline interference (50 Hz), and EMG noise. The 
temporal variations of noise and its spectral content were shown using time-frequency 
representations (STFT and spectrogram) and frequency-domain analysis. A two-stage LMS 
adaptive filter employing reference signals and a series of static notch, high-pass, and low-pass 
filters were used to filter the tainted ECG. Evaluation matrices such as Signal-to-Noise Ratio (SNR), 
Root Mean Square Error (RMSE), and R-peak detection accuracy were used to assess 
performance. Although R-peak detection accuracy was same for both static and adaptive filters 
as it just includes the correct detection of R-peaks. The viability and relative effectiveness of 
various filtering techniques for ECG denoising in real-time applications are shown in this paper. 
