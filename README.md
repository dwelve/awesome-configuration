First, make sure you have awesome, dmenu (from suckless-tools) and 
liblua5.1-filesystem installed. (I also installed lau5.1 and all the 
lua5.1 libraries). For example, on Ubuntu 12.04:

    sudo apt-get install awesome awesome-extra suckless-tools liblua5.1* lua5.1

Next, install my configuration into your awesome config folder. (Make sure that 
.config exists and .config/awesome does not exist!).

    cd ~/.config
    git clone git://github.com/dwelve/awesome-configuration.git awesome
    git submodule init

I forget why I have the submodule in there :) I think it was for icons...

Some commands (note: MOD4 is the "Windows" or Mac equivalent key):

 * MOD4-p : dmenu
   * dmenu is a smart command launcher. Just start typing in a command, and it's 
     matching system will narrow down the command choices for you. 
     For example, typing in "fox" brings up "firefox" on my system. These commands
     are located at the top of the screen (this can be configured). Hit enter and 
     the command will run. You could also type in the whole name, too.
     
Specifics:

 * I turned the "focus following the mouse" feature off.
