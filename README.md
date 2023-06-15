# Awesome Digital Mixers
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools related to digital mixers

## Contents
- [Awesome Digital Mixers](#awesome-digital-mixers)
  - [Contents](#contents)
  - [APIs and Librarys](#apis-and-librarys)
  - [Controllers](#controllers)
  - [Raspberry PI](#raspberry-pi)
  - [Integrations](#integrations)
  - [Relevant](#relevant)
  - [Documentation](#documentation)
  - [Miscellaneous](#miscellaneous)
  - [Related Lists](#related-lists)
  - [Contributing](#contributing)

## APIs and Librarys
- [Xair API](https://github.com/onyx-and-iris/xair-api-python): python interface for the Behringer XAir, Midas MR series of digital rack mixers.
- [wapi](https://github.com/pmaillot/wapi): C language API for Behringer's WING Digital Mixing Consoles
- [Allen & Heath Mixer Remote Library](https://github.com/xDGeForcexD/ah-mixer-remote): Typescript library that can be used to build your own application to control an Allen & Heath digital mixer.
- [k-mix-api](https://github.com/keithmcmilleninstruments/k-mix-api): Javascript API for fully controlling Keith McMillen Instruments K-Mix digital audio mixer / control surface.
- [ui24r-client](https://github.com/jonathanslenders/ui24r-client): Python asyncio client for the Soundcraft Ui24R digital mixer


## Controllers
- [MixGo](https://github.com/MRechtien-zz/mixgo): GO library to use MIDI messages to control digital audio mixing consoles
- [X32 OSC ESP32 remote control](https://github.com/yapweiliang/X32-OSC-ESP32-remote-control): control the Behringer X32 via WiFi using ESP32
- [XR18-Arduino-Bus-control-for-IEM](https://github.com/ksipp01/XR18-Arduino-Bus-control-for-IEM): OSC based browser control for XR 18 Aux/Bus 1-5 for Individual remote control of in-ear monitor mix

## Raspberry PI
- [X32-Recorder](https://github.com/jajito/X32-Recorder): Raspberry PI Behringer X32 Multitrack Recorder and MP3 player.
- [x32loudness](https://github.com/premultiply/x32loudness): Raspberry Pi realtime EBU R128 loudness meter display for Behringer X32 audio mixing console (and other USB audio devices)
- 

## Integrations
- [OBS-to-XAir](https://github.com/lebaston100/OBS-to-XAir): small script that mutes, unmutes and toggles groups of channels on Behringer XAir Mixers depending on the current OBS scene.

## Relevant
- https://pypi.org/project/python-osc/
- 

## Documentation
- [wiki-x-air](https://redtide.github.io/wiki-x-air/): backup of old online wiki of Behringer X-Air manual, converted to markdown.
- [Unofficial X-Air / M-Air OSC Commands List](https://behringer.world/wiki/doku.php?id=x-air_osc)
- [Unofficial X-Air / M-Air Midi Table](https://behringer.world/wiki/doku.php?id=x-air_midi)
- [Unofficial X32 / M32 OSC Remote Protocol Documentation](https://wiki.munichmakerlab.de/images/1/17/UNOFFICIAL_X32_OSC_REMOTE_PROTOCOL_%281%29.pdf)
- [Unofficial X32 / M32 Midi Table](https://behringer.world/wiki/doku.php?id=x32_midi_table)
- [WING Midi Table](https://behringer.world/wiki/doku.php?id=wing_midi_table)
- [WING Various Controls](https://behringer.world/wiki/doku.php?id=wing_various_controls)
## Miscellaneous
- [x32-proxy](https://github.com/audiopump/x32-proxy): UDP and Web Socket proxy server for Behringer and Midas digital mixer control.
- [x32_flappybird](https://github.com/adamjezek98/x32_flappybird): Flappybird game on Behringer X32 digital mixer
- [x32-fuzzer](https://github.com/GamesDoneQuick/x32-fuzzer): fuzzer built to find a reproduceable bug in the x32
- [Synchronizing a DAW with SMPTE audio data/signal](https://behringer.world/wiki/doku.php?id=smptestavesdaw): small experiment conducted on a WING and REAPER, but it should work and apply to any DAW capable of external synchronization to SMPTE data, and other mixing desks such as X32 or M32, with an SD card.

## Related Lists
- [Behringer World](https://behringer.world/): The Unofficial Behringer Forums 
## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
