# VemeGen
Command-line tool to generate vemes (video memes), including Hitler Reacts vemes, from a customizable script.

About     | Current Release
----------|-----------------------
Version   | 1.2
Date      | July 29, 2023
Platforms | macOS
License   | [MIT License](LICENSE)
Author    | Brom Bresenham

![Hitler Reacts: Outlast TV Show](Media/Outlast.jpeg)

# Installation

## New Installation

1. Install [morlock.sh](https://morlock.sh)
2. `morlock install brombres/vemegen`

## Updating Existing Installation
`morlock update vemegen`

# Usage

## Hitler Reacts Veme
    vemegen --create --type=HitlerReacts MyHRScript.txt
    # (edit MyHRScript.txt)
    vemegen MyHRScript.txt --preview  # --preview is faster
    vemegen MyHRScript.txt            # Release quality

## Custom Meme (Type "XYZ")
    vemegen --create --type=XYZ MyXYZScript.txt
    # (edit MyXYZScript.txt)
    vemegen MyXYZScript.txt --preview  # --preview is faster
    vemegen MyXYZScript.txt            # Release quality

# Examples

## Hitler Reacts: "Outlast" TV Show

### Source Script
[Examples/Hitler-Reacts-Outlast-TV-Show.txt](Examples/Hitler-Reacts-Outlast-TV-Show.txt)

### YouTube
[![Hitler Reacts: Outlast TV Show on YouTube](Media/Outlast-YouTube.jpeg)](https://youtu.be/XQt4knC_ma8)

