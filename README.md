noise-repellent
ref: https://github.com/lucianodato/noise-repellent.git
-------
broadband noise reduction.

Features
-------
* Spectral gating and spectral subtraction suppression rule
* Adaptive and manual noise thresholds estimation
* Adjustable noise floor
* Adjustable offset of thresholds to perform over-subtraction
* Time smoothing and a masking estimation to reduce artifacts
* Basic onset detector to avoid transients suppression
* Whitening of the noise floor to mask artifacts and to recover higher frequencies
* Option to listen to the residual signal
* Soft bypass
* Noise profile saved with the session

Limitations
-------
* The plug-in will introduce latency so it's not appropriate to be used while recording (35 ms for 44.1 kHz)
* It was developed to be used with Ardour however it is known to work with other hosts
 