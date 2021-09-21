# Heavy Bass Preset For EasyEffects
This is a very simple bass boosting preset for [EasyEffects](https://github.com/wwmm/easyeffects).

The idea behind this preset is to create an uncompromising bass boost by reducing treble via Equalizer, using the Bass Enhancer plugin by [Calf Studio Gear](https://calf-studio-gear.org/) to make bass punchier, and using a very soft Crystalizer to try to compensate for the reduced treble.

There are three variations.

**Heavy Bass**

    The main preset, makes the bass sound heavier. Reduces treble by about 1-6db depending on band.
**HB-Mid**

    This variant's equalizer reduces treble 25% less (0-4db) than the main preset but is otherwise unchanged.
**HB-Lite**

    This variant's equalizer reduces treble 50% less (0-3db) than the main preset but is otherwise unchanged.

It is recommended for users to try all three versions to find their preferred balance; there may also be different situations that call for a lighter/heavier treble reduction based on user preference.

# Installation

Move all `.json` files to 

`~/.config/easyeffects/output` 

or 

`~/.var/app/com.github.wwmm.EasyEffects/config/easyeffects/output`

depending on how you installed EasyEffects.

# Additional Info
The preamp is set to -5db for the bass enhancer because it is increasing bass volume by 4.5db, this is done to protect your hardware and prevent clipping.

# Trivia
I actually made this preset originally to try to make my laptop speakers not sound like crap, it was made almost haphazardly, a happy accident really, but turned out to actually sound amazing on my hardware. I then later discovered it also sounded better in my headphones than the preset I was using for that before and decided I had to be on to something here, which is what prompted me to share it.

I also actually have no idea what I'm doing with the Crystalizer, I played around with it quite a lot but the effect of the Crystalizer is typically either quite subtle (thus hard to tweak) or quite obnoxious (thus also hard to tweak anyways) there's no in-between. The Crystalizer for this preset used to be configured twice as high originally but I felt it sounded nicer when I made it milder. So if anyone has any ideas how to improve the crystalizer further, you're welcome to make an issue or pull request and I will give your suggested settings a try.
