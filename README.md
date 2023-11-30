# Teeworlds Rule Generator

The Teeworlds Rule Generator is a web-based tool designed to create rules for tile replacement in Teeworlds game maps. It offers a simple interface to generate the rules.

## Features

Dynamic Rule Generation: Automatically generates rules based on user input for tile numbers.

Customizable Parameters:
* Rule Name: Assign a unique name to each rule.
* Base Tile: Select the tile number that will be replaced.
* Border Tile: Choose the tile number for flat surfaces.
* Corner Tile Outer: Specify the tile for outer corners.
* Corner Tile Inner: Define the tile for inner corners.

Copy to Clipboard: Easily copy the generated rules to the clipboard for use in Teeworlds.

## How to Use

1. Input Parameters: Fill in the form with the desired tile numbers and rule name.
2. Generate Rule: The tool automatically generates the rule script as you input values.
3. Copy Rule: Click the "Copy Rule to Clipboard" button to use the rule in your Teeworlds map.

## Python Version

There is also a [Jupyter notebook](tw-rule-generator-gradio.ipynb) version of the tool that can be run locally. It uses the [Gradio](https://gradio.app/) library to create an interface.

## Acknowledgements

This tool utilizes Bootstrap for styling and JavaScript for its interactive features. It is intended for Teeworlds map creators and enthusiasts looking to enhance their map design process.

### Helpful Rule References

* https://www.teeworlds.com/forum/viewtopic.php?pid=92492
* https://forum.ddnet.org/viewtopic.php?t=2428
