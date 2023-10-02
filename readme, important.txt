# Remove green tint for Star Citizen Readme

The main task is to remove the green cast, apply color correction, and add a little more depth to the flat look.

What else does the preset do?
The preset raises the contours and contrasts a bit and provides a more vivid and clear image. 
Color correction is also applied. Basically, the preset provides a more natural look and natural whites and blacks.



## IMPORTANT
If you normally do not notice a green tint and Star Citizen looks normal to you, 
you should use the Reshade - Better look (green blindness).ini configuration file. 
Otherwise, the Reshade - Better look.ini configuration file may cause excessive blue shading.

I recommend testing these settings in different environments, such as hangars.



## INSTALLATION
To install this package, do the following:

1. Download the zip file and unzip it
2. copy the "Bin64" folder from this package to your Star Citizen directory.
3. replace all existing files when prompted.
4. Test both presets in different environments

Please note that this package contains some shaders that you may already have installed.

Enjoy your enhanced Star Citizen experience!



## SHADERS LIST
These shaders are used:
- Clarity.fx
- FakeHDR.fx
- Lightroom.fx
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
   - qUINT_sharp.fx