
Two sets of eight low-latency musical presets for [Easy Effects](https://github.com/wwmm/easyeffects) in 1.0, and two of two in 2.0. 

Presets with "s" suffix (mellowdEEs) are meant for external speakers and those with suffix "e" (mellowdEEe) for earphones. The former are brighter and meant for recessed, dark sounding speakers, and the latter for bright or shouty earphones.

The equalizer 2 of all mellowdEEe presets have cuts instead of boosts in the bands involving mid frequencies so as to reduce the pinna gain, that most earphones are tuned with, which some might feel shouty. If you want flat mids, see instructions below regarding muting the mid bands of EQ 2.

In case you want to try mellowdEEs presets for dark earphones and mellowdEEe presets for bright external speakers, you can very well do so by just enabling and disabling crossfeed respectively.

mellowdEEs presets add more clarity to the mid and high frequencies of my speaker setup with bottom-heavy subwoofer and mellowdEEe presets make my in-ears with too much pinna gain less shouty and more warm-neutral. When used as is, these presets barely raise the overall loudness, so they could work for most casual listening setups.

[mellowdEEe_Warm and _Bright and their variants are respectively meant for bright earphones and dark speakers but can be used interchangeably. They should work for most genres.]

**_INSTALLATION:_**

Copy the .json files to ~/.var/app/com.github.wwmm.easyeffects/data/easyeffects/output or ~/.var/app/com.github.wwmm.easyeffects/config/easyeffects/output for Flatpak; ~/.config/easyeffects/output/ for non-Flatpak GTK,  and ~/.local/share/easyeffects/output/ for non-Flatpak Qt version. Then load the Presets of choice from Easy Effects.


**_CAVEATS:_**

They can feel louder with earphones than with speakers, all the same be very careful with volume for both, more so if you are using in-ears or speakers with external DAC, AMP or DAC/AMP.

For in-ears, start with 20% volume or even less to be safe.

Also DO NOT disable the EQ 1 (that has a band of high-pass), when the music is loud enough, as it has preamp (input) set to -3 dB.


**_INSTRUCTIONS:_**

None of these presets are meant to be one size fits all (including mellowdEEe/s_Perfect) but you can make some tweaks to change their sound to suit your needs.

[While using mellowdEEs presets, if your sub or woofer needs more sub-bass, you can change the frequency of EQ 1's high-pass filter band from 50 to 20 Hz.]

[For less sub-bass while using mellowdEEe presets, unmute EQ 1's high-pass filter band and change the frequency from 20 to 50 Hz.]

You can enable bass enhancer for more bass. For music with enough bass already, though, it could make the sound muddy.

If you need less mid bass, you can mute the first band of EQ 2 for both presets.

You can also change the makeup of band 1 of multiband compressor from 0 upto -3.0 dB for less bass.

If you do not need any high-pass, you can leave the only band of EQ 1 muted for both.

Try not to change the Scope of exciters for both presets as it might bring up noise and/or make vocals and other details harsh and too sharp. You can try Scope of 5000 Hz for exciter 1, but it could sound a bit harsh, or 6000 Hz, which would feel smoother but a bit recessed.  On the other hand, 5500 Hz would retain enough details and be a safer middle ground.

You can disable the upward expander and/or compressors for a milder sound.

If even at your usual high volume level you feel the music lacks clarity, as it might on some DACs/sound cards or with music that is quiet due to it having higher dynamic range, you can increase the EQ 1's input from -3 to 0 dB or simply disable EQ 1. I sometimes do that when listening to quiet music at a lower volume for a fuller sound.

[You can flatten the EQ 2 of all mellowdEEs presets, excepting _Classical, by muting the mid bands that have frequencies between 1.1 to 4.2 kHz if you need mids with no gain. For fuller vocals, you can leave the 1.1 to 2.6 kHz bands as is.

Leave _Classical as is since it already has flat mids.

You can also mute the band with 500 Hz for all.]

[You can flatten the EQ 2 of all mellowdEEe presets, excepting _Classical, likewise by muting the mid bands that have frequencies between 1.1 to 4.2 kHz. Mute also the second last band. For fuller vocals, you can instead just mute bands that fall between 1.1 to 2.6 kHz.

For _Classical, just mute the third band. You can also mute the band with 500 Hz.]

In case you want to only boost, cut, or mute one band of EQ 2 and not the other; boost or cut the bass band or change its frequency; or boost or cut the high-shelf band; or change the scope and floor of bass enhancer, you can try whatever to make your sound better.

For near-natural sound, upward expander and compressors best be left milder as is since they can make the sound boomy with higher ratios. Upward single-band compressor especially can bring out a fatter sound with higher ratio but all things considered it is not worth it.

To make the desired changes permanent, you can have them saved by first clicking on the three dots of the active preset and then the "Save settings to this preset" option from the dropdown.


**_EQ PROVENANCE:_**

All equalizer 2 settings of mellowdEEs presets, except _Perfect, are partly based on suggestions from https://emastered.com/blog/best-equalizer-settings and https://www.musicguymixing.com/jazz-equalizer-settings/. The EQ's of _Perfect presets are mine and inspired by _Jazz EQ like all other EQ's, too, more or less are.


A work of leisure for over two years, I have tested these and variants of these presets in the last few stable Easy Effects GTK versions, the latest being 8.2.8, Qt.


If you are able, please consider supporting the devs of Easy Effects and all the amazing plugins this powerful DSP comes with.


Plugins used in these presets are: Linux Studio Plugins Equalizers (one for preamp and high-pass, one for genre), Expander (upward), Compressors (multi and single-band, both upward), and Limiter; Calf Studio Gear Bass Enhancer and Exciters (one for mid treble, one for upper treble), and bs2b Crossfeed.
