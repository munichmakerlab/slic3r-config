# slic3r-config
3d printing at the munich maker lab without having to worry about screwing up the settings

## What?
This repository contains the configurations for Slic3r Prusa Edition. These can and will be pulled automatically if installed corectly. They also function as a system preset, so you can create your own variants of these profiles and still get updates if we change anything you haven't touched in your variation.

## Installation
- get the latest version of [Slic3r Prusa Edition](https://github.com/prusa3d/Slic3r/releases)
- launch it and close the configuration dialogue
- on the top navigation menu click on "Help" => "Show Configuration Folder"
- close Slic3r for now
- download this repository as a .zip (the green "clone or download" button)
- open the .zip file next to the configuration folder
- navigate to the copy_files folder in the .zip
- copy "MuMaLab.idx" to the "cache" directory
- copy "MuMaLab.ini" to the "vendor" directory
- append the contents of "slic3r.ini_APPEND" to the end of your existing slic3r.ini
- open Slic3r again
- wait 10-20s for the configuration update to be pulled from the Internet
- close and reopen Slic3r
- you should see the prompt asking you on if you want to update the "MuMaLab" configuration => accept

Congratulations! You've successfully installed the required slic3r settings to print stuff at the Munich Maker Lab! Happy printing! 
