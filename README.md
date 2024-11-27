# Wiener-Filter-for-Prediction-and-Filtering
This project focuses on Wiener filters, a key tool in digital signal processing, designed for noise reduction, signal enhancement, and image restoration.
The project explores Wiener filters, a pivotal concept in digital signal processing (DSP), which are widely used for noise reduction, signal enhancement, and image restoration. These filters estimate a desired signal by minimizing the mean square error (MSE) between the estimated signal and the target signal. Wiener filters operate under specific assumptions such as stationarity of signals and noise, Gaussian noise distribution, and a known signal-to-noise ratio (SNR).

Key Concepts and Applications
Principle of Operation:

Wiener filters apply linear time-invariant (LTI) systems to observed noisy signals.
They use autocorrelation and cross-correlation functions to optimize the filter coefficients, achieving minimal error in the output signal.
The Wiener-Hopf equation is central to calculating these coefficients.
Image Processing:

Noise Removal: Wiener filters reduce Gaussian noise from images, preserving edges and features.
Deblurring: They address motion blur or defocus blur, restoring sharpness using deconvolution techniques like MATLAB's deconvwnr() function.
Audio Processing:

Wiener filters are employed to suppress noise in speech signals or audio recordings, using spectral properties to separate noise from the desired signal.
Applications:

Medical Imaging: Enhances clarity in MRI, CT, and ultrasound scans by reducing artifacts and noise.
Radar and Sonar: Improves target detection and tracking in noisy environments.
Remote Sensing: Removes noise from satellite and aerial images for clearer analysis.
Video Enhancement: Enhances video quality for surveillance, broadcasting, and conferencing.
