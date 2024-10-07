## Rest In Pixels

A watch face for AMOLED Garmin watches.

![Rest In Pixels Screenshot](img/rest-in-pixels-1.png)

Available from the Garmin Store here - [TBD]

### What's where

Built around a [pixel art piece](https://cara.app/post/21679689-237a-4ce4-afd9-699fbcf5c8cc) by [NandooPx](https://linktr.ee/nandoo.px), this is more of a curio than a watch face.

The last two digits of the date of birth is hours. The last two of the date of death is minutes.

![Rest In Pixels Screenshot](img/rest-in-pixels-3.png)

The birth month is the current day of the week. The death month is the battery level, 1 to 10.

![Rest In Pixels Screenshot](img/rest-in-pixels-4.png)

The name changes every 10 minutes and comes from the list of around 150, mainly populated with unusual British last names with some one-offs sprinkled in. You'll know them once you see them.

### Functional notes

In always-on mode the watch face uses image masking to facilitate burn-in protection. Luckily since it's a pixel art to begin with, the mask fits right in and only compliments the visuals.

When awoken, the watch face plays a little transitional animation to highlight HH:MM and fade in the name of the deceased. The animation is suppressed when the battery is below 20%.

This behavior can be changed by long-tapping the screen and cycling the face between "high fps", "auto fps" and "low fps" modes. "High" will play animation always, "low" will always suppress it and "auto" is the default.

### The artist

This watch face would've not existed if not for the brilliant piece of work by the artist, NandooPx, who has graciously allowed for it to be used for this project. I invite you all to check out the original and their other works over at https://linktr.ee/nandoo.px.

### Side-loading in the EU

If you are in the EU, the above Store link will likely be broken for you.

You will need to install the watch face manually, see below.

This is due to Garmin's heavy-handed interpretation of the [DSA](https://en.wikipedia.org/wiki/Digital_Services_Act)
and them hiding apps from the EU users unless the developer goes through a fairly invasive "verification" process.
Subjectively, this is hardly worth it for an app that draws a handful of digits and a colored bar on a black background.

Luckily, side-loading on Garmin watches is easy:

* Plug your watch into a computer
* Copy the watch face `.prg` file to `Garmin/Apps` folder on the watch
* Unplug the watch

The `.prg` is model-specific so pick one that matches your watch:

* [approachs7047mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4234-00/Rest%20In%20Pixels.prg)
* [approachs7042mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4233-00/Rest%20In%20Pixels.prg)
* [d2airx10](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4125-00/Rest%20In%20Pixels.prg)
* [d2mach1](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4079-00/Rest%20In%20Pixels.prg)
* [descentmk343mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4222-00/Rest%20In%20Pixels.prg)
* [descentmk351mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4223-00/Rest%20In%20Pixels.prg)
* [epix2](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B3944-00/Rest%20In%20Pixels.prg)
* [epix2pro42mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4312-00/Rest%20In%20Pixels.prg)
* [epix2pro47mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4313-00/Rest%20In%20Pixels.prg)
* [epix2pro51mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4314-00/Rest%20In%20Pixels.prg)
* [fenix7](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B3906-00/Rest%20In%20Pixels.prg)
* [fenix7pro](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4375-00/Rest%20In%20Pixels.prg)
* [fenix843mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4534-00/Rest%20In%20Pixels.prg)
* [fenix847mm](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4775-00/Rest%20In%20Pixels.prg)
* [fenixe](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4666-00/Rest%20In%20Pixels.prg)
* [fr165](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4432-00/Rest%20In%20Pixels.prg)
* [fr165m](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4433-00/Rest%20In%20Pixels.prg)
* [fr265](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4257-00/Rest%20In%20Pixels.prg)
* [fr265s](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4258-00/Rest%20In%20Pixels.prg)
* [fr965](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4315-00/Rest%20In%20Pixels.prg)
* [marq2](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4105-00/Rest%20In%20Pixels.prg)
* [marq2aviator](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4124-00/Rest%20In%20Pixels.prg)
* [venu2](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B3703-00/Rest%20In%20Pixels.prg)
* [venu2plus](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B3851-00/Rest%20In%20Pixels.prg)
* [venu2s](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B3704-00/Rest%20In%20Pixels.prg)
* [venu3](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4260-00/Rest%20In%20Pixels.prg)
* [venu3s](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4261-00/Rest%20In%20Pixels.prg)
* [venusq2](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4115-00/Rest%20In%20Pixels.prg)
* [venusq2m](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4116-00/Rest%20In%20Pixels.prg)
* [vivoactive5](https://github.com/jwdeque/Rest-In-Pixels/raw/master/prg/006-B4426-00/Rest%20In%20Pixels.prg)
