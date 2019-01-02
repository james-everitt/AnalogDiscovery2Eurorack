# AnalogDiscovery2Eurorack
Breakout board for the Digilent Analog Discovery 2 for Eurorack module testing and calibration

SSW-115-02-G-D-RA header just fits into the Analog Discovery 2, mine was a tight fit

Voltage rails and Digital I/O pins are passed through to the far header

![Alt text](AnalogDiscoveryBreakout.jpg?raw=true "Title")


# Crosstalk measurements
Initally I thought my breakout had bad high frequency performance; using the AD Bode plot function I measured crosstalk at ~-48dB from 5kHz upward. However doing the same measurement with the BNC adaptor board that Digilent offer, I measured -38dB of crosstalk in this same region! Make sense as I used a ground flood fill wherever possible, and the BNC board from digilent doesnt.

![Alt text](EurorackCrosstalk.PNG?raw=true "Eurorack measurement")
Eurorack adaptor crosstalk
<br>

![Alt text](BNCcrosstalk.jpg?raw=true "BNC measurement")
Official BNC adaptor crosstalk
