# Awesome Digital Mixers
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools related to digital mixers

## Contents
- [Awesome Digital Mixers](#awesome-digital-mixers)
  - [Contents](#contents)
  - [APIs and Librarys](#apis-and-librarys)
  - [Controllers](#controllers)
  - [Acessibility](#acessibility)
  - [Raspberry PI](#raspberry-pi)
  - [Integrations](#integrations)
  - [Relevant](#relevant)
  - [Miscellaneous](#miscellaneous)
  - [Documentation](#documentation)
  - [Related Lists](#related-lists)
  - [Contributing](#contributing)

## APIs and Librarys
- [Xair API](https://github.com/onyx-and-iris/xair-api-python): python interface for the Behringer XAir, Midas MR series of digital rack mixers.
- [wapi](https://github.com/pmaillot/wapi): C language API for Behringer's WING Digital Mixing Consoles
- [Allen & Heath Mixer Remote Library](https://github.com/xDGeForcexD/ah-mixer-remote): Typescript library that can be used to build your own application to control an Allen & Heath digital mixer.
- [k-mix-api](https://github.com/keithmcmilleninstruments/k-mix-api): Javascript API for fully controlling Keith McMillen Instruments K-Mix digital audio mixer / control surface.
- [ui24r-client](https://github.com/jonathanslenders/ui24r-client): Python asyncio client for the Soundcraft Ui24R digital mixer
- [dlive-midi-tools](https://github.com/togrupe/dlive-midi-tools): Python and midi/tcp based tool to prepare channel lists for Allen & Heath dlive & Avantis.

## Controllers
- [MixingStation](https://mixingstation.app/): cross-platform application to remote control digital mixers
- [MixGo](https://github.com/MRechtien-zz/mixgo): GO library to use MIDI messages to control digital audio mixing consoles
- [X32 OSC ESP32 remote control](https://github.com/yapweiliang/X32-OSC-ESP32-remote-control): control the Behringer X32 via WiFi using ESP32
- [XR18-Arduino-Bus-control-for-IEM](https://github.com/ksipp01/XR18-Arduino-Bus-control-for-IEM): OSC based browser control for XR 18 Aux/Bus 1-5 for Individual remote control of in-ear monitor mix
- [Reasonus](https://navelpluisje.github.io/reasonus-faderport): "Control REAPER with your FaderPort v2, 8 or 16 as it was intended"
- [X32-Edit](https://www.behringer.com/downloads.html): gives you command of the X32 remotely via computer.
- [X32-Mix](https://apps.apple.com/au/app/x32-mix/id542646451?l=pt): gives you command of the X32 remotely via an iPad.
- [X32-Q for iPhone, iPod Touch](https://apps.apple.com/pt/app/x32-q/id587363794) and [X32-Q for Android](https://play.google.com/store/apps/details?id=com.behringer.android.control.app.x32q&hl=pt_BR&gl=US): allows you to set up your personal monitoring mix with the Behringer X32 Digital Mixing Console.
- [wcc](https://sites.google.com/site/patrickmaillot/wing#h.ljsjiijwk214): Custom Control Management for WING's Snippets, Menus, and OSC
- [wxfade](https://sites.google.com/site/patrickmaillot/wing#h.30vtyc1kws44): Windows, Linux, Mac, or Rpi application for managing WING scenes.
- [wmultitake](https://sites.google.com/site/patrickmaillot/wing#h.2cjo7g6o16jr): Windows application to create recordings directly to WING with a single click.
- https://x32ram.com/products-page
- https://sites.google.com/site/patrickmaillot/wing#h.7ql1rnoc3z60
- https://sites.google.com/site/patrickmaillot/wing#h.cj0jfpy5nllp
- https://sites.google.com/site/patrickmaillot/wing#h.ov4bx6awexc3
- https://sites.google.com/site/patrickmaillot/wing#h.b09o4rh0zb1y
- https://sites.google.com/site/patrickmaillot/wing#h.x95rr22s8vfc
- https://sites.google.com/site/patrickmaillot/x32?authuser=0#h.p_T9Vt8G8nfMB-
- https://sourceforge.net/u/pvannatto/profile/


## Acessibility
- https://www.azslow.com/index.php?topic=595.0
- https://www.azslow.com/index.php?topic=597.0
- 

## Raspberry PI
- [X32-Recorder](https://github.com/jajito/X32-Recorder): Raspberry PI Behringer X32 Multitrack Recorder and MP3 player.
- [x32loudness](https://github.com/premultiply/x32loudness): Raspberry Pi realtime EBU R128 loudness meter display for Behringer X32 audio mixing console (and other USB audio devices)

## Integrations
- [OBS-to-XAir](https://github.com/lebaston100/OBS-to-XAir): small script that mutes, unmutes and toggles groups of channels on Behringer XAir Mixers depending on the current OBS scene.

## Relevant
- https://pypi.org/project/python-osc/

## Miscellaneous
- [x32-proxy](https://github.com/audiopump/x32-proxy): UDP and Web Socket proxy server for Behringer and Midas digital mixer control.
- [x32_flappybird](https://github.com/adamjezek98/x32_flappybird): Flappybird game on Behringer X32 digital mixer
- [x32-fuzzer](https://github.com/GamesDoneQuick/x32-fuzzer): fuzzer built to find a reproduceable bug in the x32
- [Synchronizing a DAW with SMPTE audio data/signal](https://behringer.world/wiki/doku.php?id=smptestavesdaw): small experiment conducted on a WING and REAPER, but it should work and apply to any DAW capable of external synchronization to SMPTE data, and other mixing desks such as X32 or M32, with an SD card.
- [wsdwatchdog](https://sites.google.com/site/patrickmaillot/wing#h.k8q88jemwkl6): Windows and Linux utility to alarm you when the time left for SD recording is falling below a given value.
- [wssaver](https://sites.google.com/site/patrickmaillot/wing#h.qinuimuwi86g): Windows and Linux screen saver program for WING
- [wrta](https://sites.google.com/site/patrickmaillot/wing#h.35z909pzb6qf): rta / meters display program showing WING RTA in a Windows canvas. 
- [Slow Mutes / Timed Mutes](https://sites.google.com/site/patrickmaillot/wing#h.i61u07v3x9tw): wapi-based program changing the behavior of WING Mutes (on all channel strips).
- https://sites.google.com/site/patrickmaillot/wing#h.h1sucwkn10wy
- https://sites.google.com/site/patrickmaillot/wing#h.asfjltealgzl
- https://sites.google.com/site/patrickmaillot/wing#h.6zrjmz7iy7wc
- https://sites.google.com/site/patrickmaillot/wing#h.c9qic7qc5uv4
- https://sites.google.com/site/patrickmaillot/wing#h.9nllcmm4ar2f
- https://sites.google.com/site/patrickmaillot/wing#h.dv89szjh9qs0
- https://sites.google.com/site/patrickmaillot/wing#h.tcr5nt8m982l
- https://sites.google.com/site/patrickmaillot/wing#h.sftix1papa7o
- 

## Documentation
- [wiki-x-air](https://redtide.github.io/wiki-x-air/): backup of old online wiki of Behringer X-Air manual, converted to markdown.
- [Unofficial X-Air / M-Air OSC Commands List](https://behringer.world/wiki/doku.php?id=x-air_osc)
- [Unofficial X-Air / M-Air Midi Table](https://behringer.world/wiki/doku.php?id=x-air_midi)
- [Unofficial X32 / M32 OSC Remote Protocol Documentation](https://wiki.munichmakerlab.de/images/1/17/UNOFFICIAL_X32_OSC_REMOTE_PROTOCOL_%281%29.pdf)
- [Unofficial X32 / M32 Midi Table](https://behringer.world/wiki/doku.php?id=x32_midi_table)
- [WING Midi Table](https://behringer.world/wiki/doku.php?id=wing_midi_table)
- [WING Various Controls](https://behringer.world/wiki/doku.php?id=wing_various_controls)

## Related Lists
- [Behringer World](https://behringer.world/): The Unofficial Behringer Forums 
## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
