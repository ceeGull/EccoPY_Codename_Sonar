# EP-Sub-Project Codename: SonarMap
![GullFrameworkImage](https://github.com/SeagullisLearningToCode/EccoPY_Codename_Sonar/blob/master/data/img/Seagull.jpg)
````
 __                     ___  __              ___       __   __
/ _` |  | |    |       |__  |__)  /\   |\/| |__  |  | /  \ |__) |__/
\__> \__/ |___ |___    |    |  \ /~~\  |  | |___ |/\| \__/ |  \ |  \
                                                    Version: 1.2 Shut Up Gull
                                                               Now with Extension "Support"
````
This is used to play around how EccoPY would look if the user ran it for now it may be restricted to MacOSX, so feel free to use it as long you give credit to me (Sound SFX and some images don't belong to me)

## Supported Operating Systems

OS | Notes |
---|-------|
MacOS | Will work the best for now, might not look the same in `.Screenshots` later.|
Windows | Not all fonts will be loaded, if so then it's defaulted to what Tkinter uses, but still will work like MacOS (in theory)|
Linux | Not tested |

## Dependencies
Here is a detailed table of what you need to run this properly (if you're planning to edit the code of course)

File | Path            | Modules  | Notes  
-----|-----------------|----------|---------|
GF.py| `data/frw/GF.py` | `Pygame 2.0.1`, `Pyglet`| Any `import` statement that targets this file is most likely going to use these modules (unless targeting a specific object but still some functions use pygame)
main.py| `main.py` | `Tkinter` (Built-in if using python 3.7 and up), `PIL` (Python Imaging Library)| `Python 3.8` or higher (to be safe about install the latest version of python), this also uses `GF.py`.

## Sources
File | Path | Source / Credit | Notes                  
-----|------|-------|---------|
ecco.bmp | `data/img/ecco.bmp` |(Sliversea) https://www.spriters-resource.com/genesis_32x_scd/ecco1/sheet/65574/ | This came from The Spriters Resource.
ecco-the-dolphin-jpeg_fade_cropped.png | `data/img/ecco-the-dolphin-jpeg_fade_cropped.png` | The Ecco Online media restoration community (https://eccothedolphin.online/media-restoration/) <br /> Original Version created by Boris Vanjello (Cover art for the Western release of the 1992 game) | I added in a fade effect and cropped the image (more additions will be made to it soon)
Seagull.jpg | `data/img/Seagull.jpg` | Image © Acabashi; Creative Commons CC-BY-SA 4.0; Source: Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Herring_gull_seagull_at_Broadstairs,_Kent,_England_06.jpg) | Image Modified by using GIMP 2.10 and a plugin called "GIMIC". Cropped (also changed the leveling) the original image Applied a Greyscale filter and GIMIC's Cutout Feature. CC-BY-SA License 4.0 (inherited from the Original Author).
GF.py | `data/frw/GF.py` | SeagullisLearningToCode | Feel free to use it
main.py | `main` | SeagullisLearningToCode | Applies to `GF.py`
