# How to install yeast.

First, you want to make sure that `grep` is installed on your system:

`sudo apt-get install grep` for Debian-based distros

`sudo pacman -S grep` for Arch Linux

To install yeast, clone this repo by doing:

`git -C ~ clone https://github.com/shebangcode/yeast`

Then, you want to go into the yeast directory:

`cd yeast`

Next, if you want to have yeast as a command, do:

`sudo cp ~/yeast/yeast /bin`

The command above is only optional.


Here is a list of the flags:

`-h`: Shows all the flags

`-a`: Searches also hidden files

`-r`: Searches recursively in the directories
