# Music Loudener

Makes music tracks very loud with minimal distortion. In most cases the end result will be just under -6 LUFS.

## Versions

### V2

The remake of the macro. It may do a better job with more calm/ambient tracks (less distortion) and it better preserves "thump" sounds.

**File names:**

- **V2: [Louden Music v2.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/Louden%20Music%20v2.txt)**
- **RC1: [v2_beta/Louden Music v2 RC1.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20RC1.txt)**
- **Beta version 1: [v2_beta/Louden Music v2 beta 1.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%201.txt)**
- **Beta version 2: [v2_beta/Louden Music v2 beta 2.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%202.txt)**
- **Beta version 3: [v2_beta/Louden Music v2 beta 3.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%203.txt)**
- **Beta version 4: [v2_beta/Louden Music v2 beta 4.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%204.txt)**
- **Beta version 5: [v2_beta/Louden Music v2 beta 5.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%205.txt)**
- **Beta version 6: [v2_beta/Louden Music v2 beta 6.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20beta%206.txt)**

### V2 RE

It's called RE (Radio Edition) since it can degrade the quality of low frequencies similar to radio tracks in GTA V. This one is v2, but optimized for use in Self Radio or anything else where quality in low frequencies may not matter as much. It uses a 1 ms limiter instead of soft clipping.

Due to the way the soft clipping works compared to using a 1 ms limiter, it has less distortion than soft clipping, so in this version, the bands are 1 dB louder before they are mixed. Results may sound slightly louder compared to the regular V2.

**File names:**

- **V2: [Louden Music v2 RE.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/Louden%20Music%20v2%20RE.txt)**
- **RC1: [v2_beta/Louden Music v2 RC1 RE.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/v2_beta/Louden%20Music%20v2%20RC1%20RE.txt)**

### Radio Edition (RE)

This version is made for Self Radio in Grand Theft Auto V. It uses a triple banded frequency decomposition and has much more dynamic range compression compared to the other versions. It's meant to mimic the new processing method for the radio tracks in GTA V.

**File names:**

- **New Version (Beta): [Loudness Enhancer RE (New).txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/Loudness%20Enhancer%20RE%20(New).txt)**
  - This version has been fixed for Audacity 3.6.0 and is slightly improved over the "normal" version. At the time of writing, 3.6.0 is currently in development, so this version is currently considered in beta.
- **Normal Version: [Loudness Enhancer RE.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/Loudness%20Enhancer%20RE.txt)**
  - Note: Only works in Audacity <3.6.0.
- **Modified Compressor Version: [Loudness Enhancer RE Modified Compressor.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/Loudness%20Enhancer%20RE%20Modified%20Compressor.txt)**
  - Note: Requires the default Compressor effect in Audacity <3.6.0 to support 0 second attack time and 100:1 ratio. Only works in Audacity <3.6.0.

### Old Version

The old and not so good version of the music loudener.

**File name: [old/Louden Music.txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/old/Louden%20Music.txt)**

### Midtones (Old Version)

Reduces treble by 6 dB in the initial decomposition process. In most cases it won't increase treble as much as the normal version.

**File name: [old/Louden Music (Midtones).txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/old/Louden%20Music%20(Midtones).txt)**

### Older Version

An old version of the old version that uses a 1 ms attack time soft limit instead of soft clipping. It reduces crackling in higher frequencies but increases it in lower frequencies. It also has no final extra limiter like in the other versions and is slightly louder.

**File name: [old/Louden Music (Old Version).txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/old/Louden%20Music%20(Old%20Version).txt)**

### Pre-Soft Clip (Old Version)

The normal version of the music loudener that doesn't apply the soft clipper or any other effects after it. This can be used if the other versions cause too much distortion.

**File name: [old/Louden Music (Pre-Soft Clip).txt](https://github.com/somefoolouthere/audacity-macros/blob/main/loudness_enhancer/old/Louden%20Music%20(Pre-Soft%20Clip).txt)**
