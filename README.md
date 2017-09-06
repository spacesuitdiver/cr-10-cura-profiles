# CR-10 Cura Profiles

This repository contains quality and material profiles for `CURA 2.7`, they *should* also work with `CURA 2.6`.

## 🛠 Installation

You can install these profiles using one of the methods below, file locations are for OSX but other O/S should have a similar location.

### via CURA

You can use CURA to manually import this profiles in the respective `Profiles` or `Materials` sections in preferences. <kbd>CMD</kbd>+<kbd>,</kbd> on OSX.

### via File System

If you name your printer `CR-10` you should be able to simply merge the quality and material directories into your `Application Support` directory. You can also install/update your profiles with the following command (unfortunately CURA doesn't support any sort of symlinking) but I suggest you select a prebuilt set of profiles and then exiting CURA otherwise it will startup not being able to load your printer profile:

```
rsync -ahv {quality,materials} ~/Library/Application\ Support/cura/2.7
```

## 💄 Qualities

### High Quality PLA

This profile is what I use for prints that are smaller (less than 100mm<sup>3</sup>) or prints that I interact with physically so I might mind the layer lines a bit more.

### Normal Quality PLA

This profile is what I use for prints that are medium to large sized (more than 100mm<sup>3</sup>).

### Normal Quality ABS

This is the same as `Normal Quality PLA` profile but sped down to 40mm/s so ABS has time to adhere to the build surface.

## 🏗 Materials

I've found both brand and color make a difference so as I buy more filaments I will test them each with a tempurature and retraction tower. The settings in these profiles are the best quality achieved without sacrificing strength. I would like to personally test each filament's strength and quality so if you'd like to send me a sample roll please messages me either here or on Twitter (@leblaaanc).

## 💪 Contributing

If you'd like to contribute to this set of profiles feel free to submit a Pull Request.

## ❤️ Give Back

If you feel these profiles have helped your prints please consider staring this repo and/or buying me a beverage 🍺 below.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](paypal.me/leblaaanc)
