# Super_Mario_Sunshine_UHD_Texture_Pack
![](https://raw.githubusercontent.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/master/GMS/gui/title/tex1_490x270_8173791dd11cea7c_5.png)
### TLDR: Free upscales and retextures of the whole game.  Check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings on the 5.0 build of Dolphin to prevent stuttering.

### 1,937 textures contributed to this pack in total
Contribution breakdown:  
qashto = 1,935   
Filipianosol = 2

[Click here to see comparisons!](../../wiki)


### -Community Requests-

title : If you're a photoshop wizard that can somehow change the [scanned high-res North American title art](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/blob/master/png/GMS/gui/title/tex1_460x304_2be218765ba946e5_5.png)'s colors to more accurately match the original in-game title art your sorcery would be appreciated.  I know it's possible it's just way outside my wheelhouse.<br>
tree shadows : Some of the original tree shadows create a white box around the trees, does anyone know how to fix this?<br>
miscellaneous fixes/improvements : If you think certain textures look bad and want to fix/improve any of the textures I've already made, post your edits on the forum and I can add them to the github.<br>
cutscenes :  This isn't a request for this pack more of an insane proposal I just want to throw out there, but if anyone is crazy enough to do frame by frame recreations of any of the cutscenes that would be nuts.  You would have my full permission to use my textures for such a project!

### -About the pack-

I've been using [waifu2x](https://github.com/nagadomi/waifu2x), a free, web-based upscaler that uses deep convolutional neural networks, and I've gotten some incredible results out of it.  I manually ran each texture through waifu2x, and inspected them, testing settings to see what looked best.  I used Bighead's Custom Texture Powershell script to make the goo and other seamless textures, big thanks to him!  A few original textures are too low-res for waifu2x to make good upscales with.  Using Gimp, I upscaled textures and manually smoothed out the edges of pollution maps, low-res banners, letters, text, and small character maps.  I also manually retextured certain textures that I felt required more than just upscaling to be acceptable in a UHD pack.  Most notably the main menu A, B, and C save blocks were retextured.  For the wanted poster, I edited a screenshot from an in-game cutscene that shows the poster at a higher resolution.

### -Recommended Settings-

Make sure to check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings on the 5.0 build of Dolphin, this will cache the custom textures to RAM when Dolphin loads the game. This will prevent all stuttering caused by using custom textures. This texture pack should only load less than 2 GB to RAM (without the goo maps) which shouldn't be a problem for computers capable of playing the game at UHD smoothly anyway.

Look at the [Dolphin wiki page for Super Mario Sunshine](https://wiki.dolphin-emu.org/index.php?title=Super_Mario_Sunshine) and follow the graphics settings configurations.  One deviation I make from that configuration is to enable Scaled EFB Copy because it makes bodies of water look way better.  I also highly recommend using V-Sync to avoid tearing.  I do not use the widescreen code on the wiki because it causes problems for me, although I've heard it works fine for others.  These are the only Gecko codes that I use:  
$60FPS (Region-Free)  
F6000002 80008180  
BF800000 3F000000  
00000000 43300000  
14000004 3F800000  
E0000000 80008000  
F6000002 80008180  
801E0074 901E0038  
801E007C 901E0078  
14000014 60000000  
E0000000 80008000  
F6000001 80008180  
40800034 C03F00D0  
D2000004 00000002  
3DC03F80 91DF00D0  
C03F00D0 00000000  
E0000000 80008000  
$16:9 Aspect Ratio (Widescreen) [NTSC-U]  
04416B74 3F9A7643  
$Remove Heatwave Effect Code NTSC-U:  
0419F83C 4E800020

Enjoy!
