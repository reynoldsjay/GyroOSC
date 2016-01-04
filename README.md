# GyroOSC
Sends gyro data from an Emotiv EPOC EEG headset as OSC messages.

Emotiv provides a program (https://emotiv.com/store/product_85.html) that sends many of the parameters that the EPOC tracks as OSC packets for use in Max/MSP, PureData, etc. This program leaves out the information gathered by the headset's gyroscope. GyroOSC adds this functionality.

GryoOSC is set up as an C++ Xcode project.

simplePatch.maxpat is a simple Max/MSP patch that receives the OSC messages from the gyroscope and prints them.
