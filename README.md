# Ship
Ship is a command line application that makes transferring files from a computer to a phone or another computer easy <br>
Ship is Developed on MacOS Catalina and should work with any Mac OS X 10.7 (Lion) or newer

# MacOS

## Installation
1. clone this repo with the lastest tag <br>
`git clone https://github.com/yusuf8ahmed/Ship.git --branch v0.0.1.3 --single-branch`
2. go into the Ship folder<br>
`cd Ship`
3. and open the terminal and run <br>
`bash install.sh`

## Uninstallation
1. Go into the Ship folder and open the terminal and run <br>
`bash unistall.sh`

# Releases
## alpha release v0.0.1.1
initial release

## alpha release v0.0.1.2
template decision error fixed <br>
text template fixed <br>
error raising error fixed <br>

## alpha release v0.0.1.3
build dist errors <br>

# Issues
## Templating
Since the template are loaded in with python format method anything the uses curly braces will cause an error which include: any Javascript function, if statments, try - execpt blocks and embedded css.

## Mimetypes 
Can only load in Mimetypes defined in the standard package "import mimetypes"