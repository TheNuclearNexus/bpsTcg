# Big Pack Suffering: The Trading Card Game
## What is this?
This is a trading card game inspired by mainly MTG & BoI
## How can I use it?
### Compiling the source
1) Install [Trident](https://energyxxer.com/trident/)
2) Clone the repository to your workspace
3) Compile the project with **Alt+Shift+X**
4) Locate the build (Should be stored in ``<project>/out/``
5) Follow from step 3 of the below 
### Downloading it prebuilt
1) Navigate to the **Releases** page
2) Download the latest datapack and resourcepack
3) Navigate to ``.minecraft/resourcepacks`` and put ``bpsTcg-resources.zip`` in the folder
4) Navigate to ``.minecraft/saves/<world you want to use>`` and put ``bpsTcg-datapck.zip`` (or ``bpsTcg`` if you compiled it) in the datapacks folder
5) Enter the world you want to use and type ``/reload`` a ``Loaded!`` message should appear in the game's chat window
6) Lastly, enable the resourcepack from the ``Resourcepacks`` tab in settings
## I want to make my own cards, can I do that?
### Yes!
**Disclaimer** In order to add your own cards you will need to compile the datapack/resourcepack yourself.
The process is not difficult but people that are not tech literate may struggle

1) Follow the steps 1 & 2 in ``Compiling the Source``
2) Naviage to ``<project>/other``
3) To add cards open ``bps_cards.tsv`` in a program such as Microsoft Excel or Google Spreadsheets, I recommend creating a copy this file first (These programs aren't necessary but will make the 
process easier)
4) Follow the format of the other cards (This can be found in the first line of the file)
5) When you are done, save the file
6) Run the python script ``generate_images.py`` (This requires some additional setup and may only work on Windows)
7) Follow the remaining steps in ``Compiling the Source``

### Help with the python script
1) You need to install [PIL](https://pypi.org/project/Pillow/)
2) You may need to install curl, to find this out open a Terminal/Command Prompt and type ``curl``
   - If you get a message saying unknown command/applet, go [here](https://stackoverflow.com/a/16216825)
   - If you get a message asking for a ``Uri`` or another parameter, then you have curl!
