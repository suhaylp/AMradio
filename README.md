# AMradio

### Project Overview
My objective was to construct an AM radio receiver and characterize each part of the circuit:

• The LRC circuit, which filters the input to select a particular carrier frequency

• The rectifier/filter used to extract the audio signal from the carrier frequency

• The amplifier used to amplify the audio signal and drive a speaker.

I worked on the detection of amplitude modulated radio signals (A.M. radio, not F.M.)

Main components of an AM radio receiver. The antenna picks up the electromagnetic radiation from nearby radio broadcast station. This is coupled (or directly connected) to the tank circuit, which is tuned so that it resonates at the carrier frequency. This results in electric current and charge oscillations in the tank circuit which in turn produces an oscillating voltage signal on input side of the diode which is proportional to the mixed radio signal. A Ge diode rectifies this signal, passing only the positive voltages. A low pass filter suppresses the high frequency spikes which occur at the carrier frequency, leaving only the modulation frequency which is the audio frequency signal. This process is called ”demodulation”. The resulting audio signal is then amplified and fed to the speaker.
