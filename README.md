# OpenCore_HPProBook440G5
Full OpenCore configuration for the HP ProBook 440 G5 (running macOS Monterey 12.3.1)


OC Version: 0.8.0
All kexts updated! 

This configuration is made for the ProBook 440 G5 by HP, the variant utilizing the dedicated GeForce 930MX, but it will work for the variants without dGPU too. 

Detailed specs: 
* Intel Core i5-8250U Quad Core CPU (KabyLake_R) @ 3,4GHz max.
* 16GB DDR4-2400 RAM (dual-channel)
* 256GB NVMe Intel 600p SSD (for Windows)
* 250GB SATA3-SSD Netac N530S (for macOS Monterey)
* Intel UHD Graphics 620 (used by macOS)
* NVIDIA GeForce GT 930MX (disabled for macOS)
* 14 inch FHD IPS screen (eDP) 
* Intel Wireless-AC 9260 160MHz with Bluetooth 5.1
* Conexant CX8200 audio codec (using alcid=23)
* Synaptics SMBus touchpad 
* Synaptics biometrics sensor (disabled, as there's no TouchID support)

What works? 
* Boot 
* Display output
* Full 3D acceleration (GPU)
* Audio 
* Microphone
* WiFi
* Bluetooth
* Sleep
* ALL USB Ports
* HP HD Camera
* Card reader
* HDMI Out
* VGA Out 
* Type-C port
* Battery readings with full info about the battery (cycles..)
* Touchpad with all gestures
* Keyboard (with brightness/volume keys working)
* etc.

What doesn't work?
* NVIDIA dGPU (not supported, no Optimus support, GPU not supported in general)
* etc..

Feel free to open a issue if you encounter any issues. Thanks!
