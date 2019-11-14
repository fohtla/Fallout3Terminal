# Fallout3Terminal

Fallout3Terminal is my own version of a Fallout 3/4/NV Terminal operating system, complete with the ability to write journal entries, and in-game sounds from Fallout 3 itself! I tried to recreate as many little details there are in the games, like the RobCo OS header and such, though you will notice I took quite a few liberties.

This is actually just a bash script that can be run from the terminal, and the output is displaying on a highly customizable retro terminal called cool-retro-terminal. 

See my demonstration video of this on reddit, the post can be found here:

[https://www.reddit.com/r/linux/comments/dw9gfw/i_recreated_a_fallout_3_terminal_as_a_linux_bash/](https://www.reddit.com/r/linux/comments/dw9gfw/i_recreated_a_fallout_3_terminal_as_a_linux_bash/)

# REQUIREMENTS

You must have the following:

* Linux based operating system
* The following packages installed:
    * pv
    * cool-retro-term
    * sox

This has not been tested on Windows, macOS, or *BSD operating systems.

# Download and run Fallout3Terminal

To run this script clone this repository, make "terminalscript" an executable , and run `cool-retro-term` as follows:

```bash
git clone https://github.com/fohtla/Fallout3Terminal
$HOME/Fallout3Terminal/terminalscript
cool-retro-term --fullscreen --noclose -e bash $HOME/Fallout3Terminal/terminalscript
```

You can also enter that command in your startup manager, as well as make launcher with it!

# Additional notes

Thank you for your interest in this! This was just a little side project that I made while sick at home, but a lot of people wanted a download!

I have decided not to leave my preset for CRT in, as some people might want to give a shot at making their own CRT preset.
Give it a shot! You might want to try a New Vegas amber look!

Believe it or not, I don't actually do a lot of this kind of thing, and I instead do a lot of Digital Art! I'm still learning, but you can check me out on [@fohtla_arts](http://instagram.com/fohtla_arts) on instagram. Otherwise, enjoy this little program I made for funsies!

