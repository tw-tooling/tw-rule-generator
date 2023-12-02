# Teeworlds Rule Generator

The Teeworlds Rule Generator is a web-based tool designed to create rules for tile replacement in Teeworlds game maps. It offers a simple interface to generate the rules.


## Features

Dynamic Rule Generation: Automatically generates rules based on user input for tile numbers.

Customizable Parameters:
* Rule Name: Assign a unique name to each rule.
* Tileset Name: The name of the tileset. Will be used for naming the downloadable file.
* Base Tile: Select the tile number that will be replaced.
* Border Tile: Choose the tile number for flat surfaces.
* Corner Tile Outer: Specify the tile for outer (convex) corners.
* Corner Tile Inner: Define the tile for inner (concave) corners.
* Corner Tile Inlay: Assign the tile for inner (concave corners, that will be put in the empty space.

Copy to Clipboard: Easily copy the generated rules to the clipboard for use in Teeworlds.

Download: Download the file that can be put into `.../data/editor/automap` to load the rules.


## How to Use

1. Input Parameters: Fill in the form with the desired tile numbers and rule name.
2. Generate Rule: The tool automatically generates the rule script as you input values.
3. Copy/Download Rule: Click the "Copy Rule to Clipboard" or "Download" button to use the rule in your Teeworlds map.
4. Copy the file to `.../data/editor/automap` or paste the code into an existing file.


## Python Version

There is also a [Jupyter notebook](tw-rule-generator-gradio.ipynb) version of the tool that can be run locally. It uses the [Gradio](https://gradio.app/) library to create an interface.


## Acknowledgements

This tool utilizes Bootstrap for styling and JavaScript for its interactive features. It is intended for Teeworlds map creators and enthusiasts looking to enhance their map design process.


### Helpful Rule References

* https://www.teeworlds.com/forum/viewtopic.php?pid=92492
* https://forum.ddnet.org/viewtopic.php?t=2428
