# Super_Mario_Sunshine_UHD_Texture_Pack

## [DOWNLOAD LINK v2.0.0 May 10th 2020](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/latest/download/GMS.7z)

![](https://raw.githubusercontent.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/master/textures/GMS/gui/title/tex1_490x270_8173791dd11cea7c_5.png)

### TLDR: Upscales and retextures for the whole game! This DDS BC7 pack does not work with v5.0 of Dolphin, it requires the latest v5.x development build. Check "Enable Cheats" in the General settings of Dolphin. Check "Load Custom Textures" and "Prefetch Custom Textures" in the Advanced tab of the Graphics settings to prevent stuttering. I know a lot of you would probably pay $60 for a SMS UHD remake from Nintendo, so if you really like this pack and appreciate the work I did [send me $60!](https://www.paypal.me/qashto/60) ...any amount is good though I guess ;)

Check out these [comparison images](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/wiki) and [in-game screenshots!](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/wiki/Screenshots)

Don't download this png repository to use in-game, use the download link above and download the GMS.7z file from the latest v2.0.x release. Put the textures in the Textures folder. GMS is SMS's game id.  
Windows: C:\Users\UserName\Documents\Dolphin Emulator\Load\Textures\GMS  
Linux: ~/.local/share/dolphin-emu/Load/Textures/GMS

## Videos of the latest Version 2.0.x (May 10th 2020)

#### [Release video showing in-game comparisons!](https://www.youtube.com/watch?v=rTuVt89yVTM)

[![](https://img.youtube.com/vi/rTuVt89yVTM/0.jpg)](https://www.youtube.com/watch?v=rTuVt89yVTM)

## Merch : Sunshine Glyphs and Warp Pipe Shirts!

These shirts were made to commemorate the release of v2 of this UHD texture pack! Available in all sizes and a few different colors.

[![](https://c.bonfireassets.com/thumb/design-image/e3a4cb6d-af15-4d39-8c08-443438bdbe1f/e4213c53-8052-4c44-ad64-9d06f2cda5e3/?size=400)](https://www.bonfire.com/sunshine-glyphs-shirt/)
[![](https://c.bonfireassets.com/thumb/design-image/c9848b30-c216-42d7-9460-e1852e02f3cb/1c8be962-c6d5-4adb-9d12-49db4f1ed6a6/?size=400)](https://www.bonfire.com/warp-pipe-shirt/)

## PS4 Button Textures

Using a PS4 controller to play? Download the [PS4 button textures add-on](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/download/v2.0.x/SMS_PS4_Button_Textures.zip) too!

## Old Videos of Version 1.4.0 (March 1st 2018)

#### English:

#### [Super Mario Sunshine HD - 1080p 60fps Widescreen | Dolphin Emulator | 2019](https://www.youtube.com/watch?v=45qFhXl4ySU)

[![](https://img.youtube.com/vi/45qFhXl4ySU/0.jpg)](https://www.youtube.com/watch?v=45qFhXl4ySU)

#### Spanish:

#### [Dolphin Super Mario Sunshine 60fps Ultra HD 4K | patch 60fps | Prueba y gameplay](https://www.youtube.com/watch?v=3yMXZgDkvmw)

[![](https://img.youtube.com/vi/3yMXZgDkvmw/0.jpg)](https://www.youtube.com/watch?v=3yMXZgDkvmw)

#### German:

#### [SUPER MARIO SUNSHINE 4K / 60FPS / HD TEXTURES GAMEPLAY](https://www.youtube.com/watch?v=49KLnur_O9U)

[![](https://img.youtube.com/vi/49KLnur_O9U/0.jpg)](https://www.youtube.com/watch?v=49KLnur_O9U)

## News Articles

[videogameschronicle](https://www.videogameschronicle.com/news/super-mario-bros-35th-anniversary/)

## About the pack

I primarily used [waifu2x](https://github.com/nagadomi/waifu2x), a free, web-based upscaler that uses deep convolutional neural networks, and I've gotten some incredible results out of it for certain textures, most notably the goo textures. I manually ran each texture through waifu2x, and inspected them, testing settings to see what looked best. I used [Bighead's Custom Texture Powershell script](https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info) to make the goo and other seamless textures, big thanks to him!

For v2.0.x I used a combination of waifu2x and Filter Forge's plastiwrap filter using a method that Dolphin forums user razius taught me. About half the pack is razius' work and half is my work to finish what he started. This was a collaboration we started two years ago but I lost interest and didn't have time to work on it back then.

## Recommended Settings

The latest 5.x Development build of Dolphin is required to use this DDS BC7 texture pack. Make sure to check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings, this will cache the custom textures to RAM when Dolphin loads the game. This prevents stuttering. I also highly recommend using V-Sync to avoid tearing.

Look at the [Dolphin wiki page for Super Mario Sunshine](https://wiki.dolphin-emu.org/index.php?title=Super_Mario_Sunshine) and follow the graphics settings configurations. One deviation I make from that configuration is to enable Scaled EFB Copy because it makes bodies of water look way better. I do not use the widescreen code on the wiki because it causes problems for me, although I've heard it works fine for others. These are the only Gecko codes that I use:

$Remove Heatwave Effect Code NTSC-U  
0419F83C 4E800020

60FPS (NTSC-U) [gamemasterplc]  
044167B8 3F800000  
042FCB24 60000000  
04414904 3CA3D70A  
C20066EC 00000002  
C2C28028 EC2105B2  
FEC00890 00000000

$16:9 Aspect Ratio (Widescreen) [NTSC-U]  
04416B74 3F9A7643

Enjoy!

## Info about Retexturing Work

Most of the textures are quite faithful to the original game with a few notable exceptions. Yet I think the pack as a whole captures and improves upon the original aesthetic of the game. Here are some explanations regarding retextures that don't look like the game's original textures:

- razius' tree textures do not look like the originals in the game but I agree with the changes. The original textures are just way too simple and replicating their aesthetic would look wrong in a UHD pack.
- In Noki Bay I used a bit of artistic license to make textures that are quite different. The granite textures are some of the largest in the game. Instead of having a variety of smaller textures for the many walls in this area the game only uses two textures for all of them. The upscales of the original textures looked nice from a distance but weren't detailed enough when playing the level at 4K. I used a combo of waifu2x and Filter Forge's Bad Trip filter. I went through a lot of variations to get good results from this method.
- I kind of redesigned the boats in Delfino Plaza cause the original texture is so tiny for such a large asset. If you want to play that one Delfino Plaza level you have to access with Yoshi you're gonna spend a good amount of time on these boats lol. Luckily I could source the wood textures, roof hatching, and bamboo doors from larger textures in the game. I think it turned out great.
- The signs in the game use a tiny texture with cute little drawings on them but they're way to small to upscale. I made some drawings of my own inspired by these drawings.

## Info about PNG vs DDS

This repo has png files only for people that want to see the source files that I used to make the DDS texture pack.  Trying to use the png files will cause Dolphin to allocate 9GB of memory to the textures and make the game less playable or unplayable depending on your hardware.  Using the DDS pack will only cause Dolphin to allocate 2.4GB.  This occurs because the PNG files are loaded into memory completely uncompressed (really bad for big textures) and the DDS texture files are compressed. With the DDS pack gameplay should be smooth 60fps at 4K even if you have even entry level gaming hardware (as of 2020).

## Resources

If anyone reading this wants to make their own texture pack, here's some links to the websites, apps, and other resources I used:<br>

[Filter Forge](https://www.filterforge.com/)  
[waifu2x web](http://waifu2x.udp.jp/)  
[waifu2x batch web](http://waifu2x.me/)  
[waifu2x desktop](https://github.com/lltcggie/waifu2x-caffe/releases)  
[CUDA](https://developer.nvidia.com/cuda-downloads)

Also check out [Bighead's custom texture tool](https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info) which is very good for creating seamless textures, doing file conversions, optimizing png files, and other things that would be quite awful to do manually.

I would test some textures using the waifu2x web version and the desktop version to see which will be faster for you. If you don't have an NVIDIA graphics card and CUDA acceleration you might want to just stick with the web version, however if your internet speed isn't that good definitely use the desktop version even if it's just using your CPU.

## Donate!

Patreon:
[https://www.patreon.com/qashto](https://www.patreon.com/qashto)

Paypal:
[https://www.paypal.me/qashto/5](https://www.paypal.me/qashto/5)
