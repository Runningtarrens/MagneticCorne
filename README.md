# Mcorne
![28816_Mcorne_Banner](https://user-images.githubusercontent.com/65970993/142192291-f98b4d5c-05fb-46df-812c-ea15619faf7e.jpg)


This is the Repository for a Magnetic Case for the Corne keyboard.


![20211104_104911](https://user-images.githubusercontent.com/65970993/142194100-e0e1e61c-e03f-4065-9170-004b7698ddeb.jpg)


Content:

* Preface
* The case
* Bill of Materials
* How to print
* Files
* Tangented
* More Pics
* Legend


# Preface

If you build a lot of keyboards or repair them, you know the hassle of having to open the cases, screw/ unscrew and taking apart the whole thing everytime you need to reflow a solder point, an led or maybe even just reset the MCU. Also for any corne build youll need to have about 20 screws and 5 standoffs per half to just keep the halfs together. With the Mcorne you dont need to unscrew anything to access the PCB or any screw or standoff to use this case. The Case supports magnetic tenting legs and provides tenting holes for other tenting methods.

Feel free to join the Discord Server, if you have questions about the case or just want to have a chat: https://discord.gg/TRQFN7fyU5


# The Case

![MagneticCorne2](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124131.jpg)
![MagneticCorne3](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095158.jpg)
![MagneticCorne4](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095136.jpg)

# Bill of Materials

To print this case youll need:
* about 120 gramms of Filament
* 16 Neodymium Magnets (14mm x 4mm x 2,5mm)
*  (Optional) 4 Neodymium Magnets round (10mm x 1mm)

# How to print
 
 I always print in PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with, because if you want to put the magnets in, you have to open the enclosure and might be having problems with warping or cracked prints because of that.

## Slicing

### Settings for the Print:

* 0.10 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp

### Getting the magnets in

To get the magnets in, the M600 command is used. The printer makes a pause and removes the filament from the extruder. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to each other and dont repel each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is.

### Top
The print is paused on the top half after the 42 layer or 4.2mm hight.
![MagneticCorne5](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140316.png)


#### Position of the Pockets for the Magnets
![MagneticCorne6](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140616.png)



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting and a transparent basis, 3 pauses. 2 to get the magnets in and 1 to just change the filament. If you dont want magnetic tenting and dont want another colour for the top part, youll only need one pause for the magnets.

#### Overview of the Part.

![MagneticCorne7](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bottom%20slice.JPG)

#### First pause for the round magnets needed for the tenting

![MagneticCorne8](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%201.JPG)


#### Second pause to change the filament (different colour)

![MagneticCorne9](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%202.JPG)


#### Third pause for the magnets to close the case

![MagneticCorne10](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%203.JPG)


# Files

## latest files

* corne split_bot_rechts_v4.stl
* corne split_top_right_reinforced_tentless_v4.stl
* corne split_top_right_reinforced_v4.stl

Version v4 is the latest for the case. I made some corrections so the inner keys ( T and Z dont scratch on the case).
I only uploaded the right side as .stl but you can just mirror it in your slicer software to get the left version of it. 


The .stl are to slice yourself. There are also .3mf files which are already dialed in and provide the exact settings i use.


# Tangented

* Magnetic tenting legs - soon
* Mcorne Travel Case 
* Keycaps - soon




# More Pics

![MagneticCornegif1](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095457_1.gif)
![MagneticCornegif2](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095457_2.gif)


#### Bottom

![MagneticCorne11](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124627.jpg)


#### Top underside

![MagneticCorne12](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124807.jpg)


#### Top upside

![MagneticCorne13](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124826.jpg)


#### USB Port

![MagneticCorne14](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124300.jpg)


#### TRS Port

![MagneticCorne15](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124229.jpg)


#### Detail view 

![MagneticCorne16](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124309.jpg)


#### Detail view close up

![MagneticCorne17](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124406.jpg)


# Legend

* MCU = Microcontroller unit

