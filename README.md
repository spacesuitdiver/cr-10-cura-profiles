# CR-10 Cura Profiles

This repository contains quality and material profiles specific to the Creality CR-10 printer for `CURA 3.0`, they *should* also work with `CURA 2.7` and `CURA 2.6` as they only apply basic settings available to each of these versions but you may have to change the settings_version in the `[metadata]` section of the file.

## 🛠 Usage

### Installation

You can install these profiles using one of the methods below, file locations are for OSX but other O/S should have a similar location.

#### via CURA

You can use CURA to manually import this profiles in the respective `Profiles` or `Materials` sections in preferences using <kbd>CMD</kbd> + <kbd>,</kbd> on OSX.

#### via File System

If you name your printer `CR-10` you should be able to simply merge the quality and material directories into your `Application Support` directory. You can also install/update your profiles with the following command (unfortunately CURA doesn't support any sort of symlinking) but if you are updating be sure to select a prebuilt set of profiles and then exit CURA otherwise it will startup not being able to load your printer profile:

```
rsync -ahv {quality,materials} ~/Library/Application\ Support/cura/3.0
```

### Bed Adhesion

* *PLA* - These profiles are intended to yield working results directly on glass simply with a heated and *level* bed but you should hedge your bets and use a light coat of glue stick. I do use an IKEA mirror because the stock glass I could not level.
* *ABS* - This profile worked with painters tape on the bed. I could not get the glue stick to work as it seemed to evaporate, I intend to move on to PEI as soon as it's in stock and provide some more print settings and suggestions

## 💄 Qualities

No quality will have supports or ironing enabled by default however simply enabling either should yield good results as I've tweaked them a bit.

### High Quality PLA

This profile is what I use for prints that are smaller (less than 100mm<sup>3</sup>) or prints that I interact with physically so I might mind the layer lines a bit more.

### Normal Quality PLA

This profile is what I use for prints that are medium to large sized (more than 100mm<sup>3</sup>).

### Normal Quality ABS

This is the same as `Normal Quality PLA` profile but slowed down to 40mm/s so ABS has time to adhere to the build surface.

## 🏗 Materials

I've found both brand and color make a difference so as I buy more filaments I will test them each with a tempurature and retraction tower. The settings in these profiles are the best quality achieved without sacrificing strength. I would like to personally test each filament's strength and quality so if you'd like to send me a sample roll please messages me either here or on Twitter (@leblaaanc).

## 💪 Contributing

If you'd like to contribute to this set of profiles feel free to submit a Pull Request.

## ❤️ Give Back

If you feel these profiles have helped your prints please consider staring this repo and/or buying me a beverage 🍺 below.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/leblaaanc)
