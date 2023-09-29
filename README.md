# Better look and remove green tint for Star Citizen

The main task is to remove the green tint, make a color correction and give the flat look a little more depth. 

The green tint is one of those things that not all people can see. You can easily test if you have red-green blindness [on this website](https://www.colorlitelens.com/color-blindness-test.html#Redgreen). You can also check out the first screenshot at Maria Hospital.

We, who see green tones almost 100%, have to correct the image in Star Citizen if the green tint bothers us. And that's exactly what this preset does.  

### What else does the preset do?
The preset raises the contours and contrasts a bit and provides a more vivid and clear image. Color correction is also applied. Basically, the preset provides a more natural look and natural whites and blacks.



## IMPORTANT
If you normally do not notice a green tint and Star Citizen looks normal to you, you should use the "Reshade - Better look (green blindness).ini" configuration file. Otherwise, the "Reshade - Better look.ini" configuration file may cause excessive blue shading.

I recommend testing these settings in different environments, such as hangars.




## INSTALLATION
To install this package, do the following:

1. Download the [zip file](https://github.com/rjcncpt/StarCitizenBetterLookReshade/releases) and unzip it
3. copy the "Bin64" folder from this package to your Star Citizen directory.
4. replace all existing files when prompted.
5. Test both presets in different environments

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
