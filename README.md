# musicLED
#### Description
This is a Windows forms application that reads audio data generated by the computer (aka. what your PC outputs) and sends it to a serial port. On the other side I have an Arduino Leonardo that reads the RGB values and outputs them onto an addressable LED strip

---

#### Demo
To test it out you can just build it, flash your arduino with something like: [Example sketch](musicLED_Arduino/musicLED_Arduino.ino)  
Note that this example Arduino sketch requires the [FastLED library](https://github.com/FastLED/FastLED)

---

#### Coming soon-ish:
  + better adjustment for varying sound volume levels across different types of content
  + custom gradients
  + settings that will actually get saved
  + hue shift slider
  + a button that will enable the LEDs to display different pattrens when there is no sound so the LEDs could also be used to light up the room

---

#### Other
I hope this helps anyone. I started this project to improve my setup a bit and it turned out great. I decided to share this project on GitHub since other GitHub projects helped me learn a lot about programming and this is how I'm now trying to give back to the community.

If you have any questions, suggestions etc. email me at: janleskovec.dev@gmail.com

---
