# Super_Mario_Sunshine_UHD_Texture_Pack

## [DOWNLOAD LINK](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/latest/download/GMS.7z)

![](https://raw.githubusercontent.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/master/textures/GMS/gui/title/tex1_490x270_8173791dd11cea7c_5.png)

### TLDR: Upscales and retextures for the whole game! This DDS BC7 pack does not work with v5.0 of Dolphin, it requires the latest v5.x development build. Check "Enable Cheats" in the General settings of Dolphin. Check "Load Custom Textures" and "Prefetch Custom Textures" in the Advanced tab of the Graphics settings to prevent stuttering. I know a lot of you would probably pay $60 for a SMS HD remake from Nintendo, so if you really like this pack and appreciate the work I did [send me $60!](https://www.paypal.me/qashto/60) ...any amount is good though I guess ;)

[Click here to see comparison images!](../../wiki)

## Videos

COMING SOON!

## Old Videos of Version 1.4.0

#### English:

#### [Super Mario Sunshine HD - 1080p 60fps Widescreen | Dolphin Emulator | 2019](https://www.youtube.com/watch?v=45qFhXl4ySU)

[![](https://img.youtube.com/vi/45qFhXl4ySU/0.jpg)](https://www.youtube.com/watch?v=45qFhXl4ySU)

#### Spanish:

#### [Dolphin Super Mario Sunshine 60fps Ultra HD 4K | patch 60fps | Prueba y gameplay](https://www.youtube.com/watch?v=3yMXZgDkvmw)

[![](https://img.youtube.com/vi/3yMXZgDkvmw/0.jpg)](https://www.youtube.com/watch?v=3yMXZgDkvmw)

#### German:

#### [SUPER MARIO SUNSHINE 4K / 60FPS / HD TEXTURES GAMEPLAY](https://www.youtube.com/watch?v=49KLnur_O9U)

[![](https://img.youtube.com/vi/49KLnur_O9U/0.jpg)](https://www.youtube.com/watch?v=49KLnur_O9U)

## About the pack

I primarily used [waifu2x](https://github.com/nagadomi/waifu2x), a free, web-based upscaler that uses deep convolutional neural networks, and I've gotten some incredible results out of it for certain textures, most notably the goo textures. I manually ran each texture through waifu2x, and inspected them, testing settings to see what looked best. I used [Bighead's Custom Texture Powershell script](https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info) to make the goo and other seamless textures, big thanks to him! A few original textures are too low-res for waifu2x to make good upscales from. Using Gimp, I manually upscaled a few textures: low-res banners, letters, text, and small character maps. I also manually retextured certain textures that I felt required more than just upscaling to be acceptable in a UHD pack. Most notably the main menu A, B, and C save blocks were retextured. For the wanted poster, I edited a screenshot from an in-game cutscene that shows the poster at a higher resolution.

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

## Resources

If anyone reading this wants to make their own texture pack, here's some links to the websites, apps, and other resources I used:<br>

This is the web version:<br>
http://waifu2x.udp.jp/

Here's a web version that can do batches of textures:<br>
http://waifu2x.me/

Here's the desktop version I used, scroll down to the zip which contains the precompiled exe (not the source zip) and download it:<br>
https://github.com/lltcggie/waifu2x-caffe/releases

CUDA download, you will have to make an account:<br>
https://developer.nvidia.com/cuda-downloads

Also check out Bighead's custom textures post and his custom texture tool which is very good for creating seamless textures, doing file conversions, optimizing png files, and other things that would be quite awful to do manually:<br>
https://forums.dolphin-emu.org/Thread-dolphin-custom-textures-info

I would test some textures using the waifu2x web version and the desktop version to see which will be faster for you. If you don't have an NVIDIA graphics card and CUDA acceleration you might want to just stick with the web version, however if your internet speed isn't that good definitely use the desktop version even if it's just using your CPU.

## Donate!

Patreon:
[https://www.patreon.com/qashto](https://www.patreon.com/qashto)

Paypal:
[https://www.paypal.me/qashto/5](https://www.paypal.me/qashto/5)
