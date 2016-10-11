# JQI Eagle Configuration Repository

This repository contains all of the libraries and scripts used at the JQI to turbo-charge your Eagle!

## Installation

Clone the repository somewhere on your machine. Then, open Eagle, and from the Eagle Control Panel, select `Options -> Directories`. Add the apropriate paths to your environemnt variables, eg, 

    $EAGLEDIR/lbr:/path/to/lbr-jqi

Repeat for the design rules, scripts, ULPs, etc.

## Enabling advanced menus with JQI customizations

Copy the file eagle.scr inside scr-jqi into the default eagle scr library ($EAGLEDIR/scr)
It is suggested to rename current eagle.scr into eagle_old.scr so that it will be possibile to restore it

Copy all the files in the directory icons into the same directory where eagle binary files are installed: this will add all JQI customized icons to the Eagle GUI.




## Project versioning

This repository is for "configuration" files, eg, a condensed set of libraries and scripts for the power user.

We also have a repository for versioning and sharing eagle projects. Update with link once created...
