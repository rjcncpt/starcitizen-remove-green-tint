# Star Citizen "Reshade Better look" Readme

The main task is that the preset removes the green shading and performs a color correction.
The green shading is such a thing, not all people see it. You can discuss this endlessly :)
Many people have red/green blindness and they do not see slight green or red shades. 
Which is why the image is seen as neutral for these people. 

We who see green shading have to correct for that. And that's what this preset does. 
The preset also raises the contours a bit and makes for a more vivid and clear image. 
The look also goes a bit in the blue/purple direction. It's just more natural.



## IMPORTANT
Star Citizen may have a slight green shading effect that varies in intensity.
If you do not notice green shading, you should use the configuration file "Reshade - Better look (green blindness).ini".

Otherwise, the "Reshade - Better look.ini" configuration file may result in excessive blue shading.

We recommend testing these settings in different environments, e.g. hangars.




## INSTALLATION
To install this package, do the following:

1. Download the zip file and unzip it
   https://github.com/rjcncpt/StarCitizenBetterLookReshade/releases
3. copy the "Bin64" folder from this package to your Star Citizen directory.
4. replace all existing files when prompted.

Please note that this package contains some shaders that you may already have installed.

Enjoy your enhanced Star Citizen experience!



## SCREENSHOTS
Vanilla -> Reshade

![image](https://i.imgur.com/rcntFdI.png)
![image](https://i.imgur.com/ZkXsc5e.jpg)

![image](https://i.imgur.com/rWWkoT7.png)
![image](https://i.imgur.com/vdxQvoi.jpg)

![image](https://i.imgur.com/hXDgs55.jpg)
![image](https://i.imgur.com/K7RQun5.jpg)

![image](https://i.imgur.com/rkkHm0M.png)
![image](https://i.imgur.com/SRLi0nn.jpg)

![image](https://i.imgur.com/HI8Ktng.png)
![image](https://i.imgur.com/VyMfaEq.jpg)



## SHADERS LIST
These shaders are used:
- Clarity.fx
- ContrastStretch.fx
- FakeHDR.fx
- Lightroom.fx
- LumaSharpen.fx
- ReShade.fxh 	(is needed to compile the shaders)
- ReShadeUI.fxh (is needed to compile the shaders)
- Tonemap.fx
- Tonemap.fxh

-- PD80 (https://github.com/prod80/prod80-ReShade-Repository/tree/master/Shaders)
   - PD80_01B_RT_Correct_Color.fx
   - PD80_03_Filmic_Adaptation.fx
   - PD80_06_Film_Grain.fx

-- qUINT (https://github.com/martymcmodding/qUINT/tree/master/Shaders)
   - qUINT_lightroom.fx
