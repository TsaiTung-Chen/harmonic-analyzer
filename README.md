# harmonic-analyzer
Harmonic analysis implementation based on the Farina’s method described in [Simultaneous measurement of impulse response and distortion with a swept-sine technique](https://www.researchgate.net/publication/2456363_Simultaneous_Measurement_of_Impulse_Response_and_Distortion_With_a_Swept-Sine_Technique) by Angelo Farina.

By this tool, we can separate the linear response and harmonic responses from the microphone recording of a logarithmic sweep, and show the estimates of the transducer system's fundamental frequency response, THD, and rub & buzz.

The logarithmic-swept-sine excitation signal (in WAV format), is generated by this tool but the recording process should be done using any other recording software. Once the recording process is done, you can load the recorded WAV file to proceed to analyze the system response.
