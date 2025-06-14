**motivation**

I have an old Yamaha Clavinova CLP-840 in almost good condition. Expect the soundboard, it's totaly broken. But using an MIDI interface, Audio IN and deactivating the soundgeneration of the Clavinova sound generation can happen outside.

I use an old Raspberry PI 2 with fluidsynth running as a service. Everything works fine. Fluidsynth "understands" almost every key, pedal, setting of the piano.. But, there are more possibilities than buttons. That's why i'd like to have more control over what is going on and some kind of stable initialization of the whole system during system start.

Let's start..

**targets**
- build a secure web-interface (http(s)) for lan (no access from outside)
- configurable design in mind
- control fluidsynth daemon (service) on localhost over telnet
- change fonts (soundfonts)
- change instruments (for channel 0)
- change gain
- ...

**future**
- get and display some midi information
- control fluidsynth with midi data (e.g. if key 71 pressed select next intrument)
- enable audio playback of files (any type) and streams (sources: filesystem, BT, ..) / switch between playback and synth
- integrate into Google Nest / Home
- ...
