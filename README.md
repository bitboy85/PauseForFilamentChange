# PauseForFilamentChange

This script is designed to work with Cura 4.4.0+ to help with Filament change during print.
I've tested it on Ender 3 pro with silent board installed where the stock firmware is missing the advanced_pause_feature.
Its based on the original file from  https://github.com/Ultimaker/Cura/blob/master/plugins/PostProcessingPlugin/scripts/PauseAtHeight.py

Because its very easy to accidentally move the z axis while changing the filament it includes 2 options to prevent this issue.
1. It locks z axis and frees Extruder for more easy change of filament
2. It allows to reset (home) z axis if moved. Make sure the machine cannot hit what you've already printed while it moves down.

## Installation
Just copy to your scripts dir (Cura -> Help -> Show configuration folder -> scripts) and start cura.
