# CraftPy

CraftPy is a Minecraft Inspired game created in Python.


## Credits
Credits to Michael Fogleman for the base sourcecode to this project!
https://github.com/fogleman/Minecraft

## How to Run

	First, clone the Repo to a folder on you PC:
		git clone https://github.com/Seshpenguin/Minecraft.git
	Then run CraftPy!
		python main.py
	If you dont have Pyglet installed, first type "pip" into your CMD, if that doesnt work, run this command, if it doesnt, skip to the next:
		python get-pip.py
	Than install pyglet:
		pip install pyglet
	If Pip isnt working, then you may have to add it to your Enviroment Variables.
	First, find the folder Pip is on your system (For me its at: C:\Program Files\Python 3.5\Scripts\),
	then add that folder to your Enviroment Variables (Google how to do that)
NOTE: These instructions were made for Windows (In my case, Windows Server 2012 R2/Windows 8.1)

### Mac

On Mac OS X, you may have an issue with running Pyglet in 64-bit mode. Try running Python in 32-bit mode first:
    arch -i386 python main.py

If that doesn't work, set Python to run in 32-bit mode by default:
    defaults write com.apple.versioner.python Prefer-32-Bit -bool yes 
	
This assumes you are using the OS X default Python.  Works on Lion 10.7 with the default Python 2.7, and may work on other versions too.  Please raise an issue if not.
  
Or try Pyglet 1.2 alpha, which supports 64-bit mode:  
    pip install https://pyglet.googlecode.com/files/pyglet-1.2alpha1.tar.gz 

## How to Play

### Moving

- W: forward
- S: back
- A: strafe left
- D: strafe right
- Mouse: look around
- Space: jump
- Tab: toggle flying mode

### Building

- Selecting type of block to create:
    - 1: brick
    - 2: grass
    - 3: sand
- Mouse left-click: remove block
- Mouse right-click: create block

### Quitting

- ESC: release mouse, then close window


###
~Seshpenguin