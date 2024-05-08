# AB_ScrewGenerator
Screw, bolt, and general connector decal generation utility for use with Substance Designer/Painter.
![image info](https://raw.githubusercontent.com/DavidHGillen/AB_ScrewGenerator/main/_images/Banner.png)

## About
When working on a model I needed to add some screws at key points to round out the detailing; however, I was unimpressed with the options I found for free. I decided to write a general purpose utility anyone could use. While far from perfect, I added features that would allow all the types of connectors I could think of. From Self tapping woodscrews, to PC Hard Drive screws, to large industrial bolts, and ended up with something that could even make passable sci-fi nonsense.

This is released under MIT for anyone to do with as they will. But not to the extent that I don't appreciate the credit for my work. Especially when used on bigger projects. PRs or bug reports are welcomed.

David "Angry Beaver" Gillen

# Usage

## How to install as a user
Download the .sbar file from this website, [a handy link](https://github.com/DavidHGillen/AB_ScrewGenerator/blob/main/AB_ScrewGeneratorPlus.sbsar):
![image info](https://raw.githubusercontent.com/DavidHGillen/AB_ScrewGenerator/main/_images/DownloadLocation.png)

Once you have the .sbar you're good to go. Just load it into whatever will take it. Everything else is for development or documentation of the tool and isn't needed.
If you don't have any Substance applications then you might be able to use it with a Substance plugin for a game engine like Unreal or Unity.

## Quick Substance Painter How to use
* Open your Substance Painter project
* Import the new resource to your project/session/library
![image info](https://raw.githubusercontent.com/DavidHGillen/AB_ScrewGenerator/main/_images/ImportLocation.png)
* Add a Fill layer, brushes and more work too, but for now we'll use a fill
* Drag the screw generator onto the "material mode" for your layer
![image info](https://raw.githubusercontent.com/DavidHGillen/AB_ScrewGenerator/main/_images/MaterialLocation.png)
* For this layer set the AO, Height, and Normal blending to "Normal" mode. The screw should replace what's below it, not mix into it
* Set the generator's settings as desired, it often helps to start from one of the presets
* Adjust the projection of the fill layer as desired so your screw is in place
* Repeat as desired

## Features
* Two surface toggle for different texturing for inset vs head
* Outer stylization for including insets and other details with the screw
* All layers appropriately masked to make usage simple in complex setups
* Extra grayscale outputs generated for custom work including head and inset shape
* Image inputs for colour, roughness, and metalness so users can choose the type of metal to taste
* Define the generator's output as an anchor layer and update your whole model with changes at once

# Cheatsheet
While this isn't all the controls it should give you an idea of how they work with each other to create the final result.
![image info](https://raw.githubusercontent.com/DavidHGillen/AB_ScrewGenerator/main/_images/ScrewGenerator_Cheatsheet.png)