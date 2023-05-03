# Teensy4-audio-carrier

Audio carrier board for teensy 4 and 4.1

## Specs and features

* Audio codec : WM8731 (stereo 24bit 96Khz max)
* SPI display 2.8'' ILI9431 (240RGBx320 Resolution & 262K color)
* I2C EEPROM 256kb
* 25x potentiometer (multiplexed)
* 1x rotary encoder
* Line output
* Headphone output
* MIDI support : in, out, thru

## Drivers and libraries (Install from Arduino IDE or VSCODE+PLATFORMIO)

* Rotary : https://www.pjrc.com/teensy/td_libs_Encoder.html
* Debounce switch :https://www.pjrc.com/teensy/td_libs_Bounce.html
* Potentiometer noise filter : https://github.com/dxinteractive/ResponsiveAnalogRead
* Display : https://www.pjrc.com/store/display_ili9341_touch.html
* Multiplexer : https://github.com/waspinator/CD74HC4067
* Audio codec : https://github.com/PaulStoffregen/Audio (already installed in teensyduino)
* MIDI : https://github.com/FortySevenEffects/arduino_midi_library
