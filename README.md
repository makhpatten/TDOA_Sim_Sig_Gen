# TDOA_Sim_Sig_Gen

SIMULNK project to generate data for TDOA algorithm processing.
This is a baseband simulation of a transmitted signal received at three distantly located revceivers.
The received signal at each transmitter is delayed relative to the other receivers, to simulate the defined geometry of transmitter and receivers.
White noise is added to simulate receiver noise, and frequency offset, drift, and random jitter is introduced to simulate non-perfect receivers.
The data is saved to .mat files, to be processed by algorithms to perform time difference of arrival estimation, and using the estimated time differences to geolocate the transmitter.

