# ESP32-S3-Toy
This is a personal project with the aim of building a ESP32 based toy with the following functionalities:
- RFID card reader & writer
- Local music player w/ bluetooth & wifi capabilities
- 2.4 Ghz "jammer"
- LoRa communication device
- (Works) Display & buttons for control

# Progress - what works 
- Display w/ 5 buttons used for navigation
- RFID module can read and dump its output in the serial monitor, but it cannot write or display anything on the actual screen module
- 2.4 Ghz jammer works, but I don't have any capacitors *yet* so the performance is unstable (I assume that's why anyway)

# Modules Used
- (1x) ESP32-S3 (microcontroller)
- (2x) NRF24L01+PA+LNA modules (for 2.4 Ghz jamming)
- (1x) RC522 module (RFID reader & writer)
- (5x) Buttons
- (1x) 0.96 Inch OLED Display module

# AI Use POlicy
With this being a personal project, intended as a hobby and for learning, the use of AI is limited as such:
- Explaining code available online
- Fixing errors which stump me for more than 2-4 days (meaning I gave up)
Given this, please do not expect frequent updates or to put bluntly, anything functional unless explicitly stated in the progress section

# Schematic 
Will be done sometime! I will try to make it as easy to interpret as possible such that anybody with little to no experience can follow along. Along the way I'll also try to explain anything that is not just "plug and play"
