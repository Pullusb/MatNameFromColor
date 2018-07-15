# MatNameFromColor
Blender addon - Rename marterial by its closest english name color

**[Download latest](https://raw.githubusercontent.com/Pullusb/MatNameFromColor/master/MatNameFromColor.py)** (right click, save Target as)

--------

Description:

Add 4 buttons in the 'settings' panel of the material

Rename from viewport - rename the material according to its viewport color
Rename from nodes - rename the material according to nodes (experimetal, try to find a node with color)
copied color name to clipboard - if you have a color copied in the clipboard, the clipboard will be replaced by the name of the color
Set viewport color from node - try to find a node with color and apply it to viewport color


Call the *copied color name to clipboard* from anywhere : In the search bar look for '*convert clipboard color to name*'

#### note:
this addon use *webcolors* module (will propose to download automatically at first use)

However, if you want to install it manually follow this:

*Webcolors* install note
- STEP 1 - download the module:  
Method A: with PIP: using command "pip install webcolors"  
the webcolors.py module will be in the site-packages folder ("yourLocalFolder.../Python/Python35/Lib/site-packages")  
Method B: directly get the file from github > https://github.com/ubernostrum/webcolors/blob/master/webcolors.py
  
- STEP 2 - copy the webcolors.py module in the blender modules folder of your version  
exemple on windows, located in : *C:\Program Files\Blender Foundation\Blender\2.79\scripts\modules*
