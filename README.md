First, make sure you have awesome, dmenu (from suckless-tools) and 
liblua5.1-filesystem installed. (I also installed lau5.1 and all the 
lua5.1 libraries). For example, on Ubuntu 12.04:

    sudo apt-get install awesome awesome-extra suckless-tools liblua5.1* lua5.1

Next, install my configuration into your awesome config folder. (Make sure that 
.config exists and .config/awesome does not exist!).

    cd ~/.config
    git clone git://github.com/dwelve/awesome-configuration.gitawesome
    git submodule init

I forget why I have the submodule in there :) I think it was for icons...
