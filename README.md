# Tilix Theme(s)
Everyone have a different taste, not only we want app that can run and meet our requirement but we also love the eye candy thingy....if you using [Tilix](https://github.com/gnunn1/tilix) (previously known as Terminix) and looking for other theme which are not shipped by default, consider your're lucky because this repo have a huge collection of themes which I gather from the net and ported to use with Tilix + 1 extra theme that I made especially for Tilix Terminal....[Terminix Dark](https://github.com/storm119/Tilix-Themes/blob/master/Themes/terminix-dark.json) and NOT forget to mention from the contributors by submitting the new themes dedicated to Tilix community.

### Notes:
* 1: Related to this discussion [#380](https://github.com/gnunn1/terminix/issues/380)
* 2: I'm using Tilix + [Linux Mint 18.2 Sonya (Cinnamon)](https://www.linuxmint.com/) + [Fish](https://github.com/fish-shell/fish-shell) + [NeoVim](https://github.com/neovim/neovim) + other plugins.



### How to use:
* You need to install Tilix from [Tilix Git](https://github.com/gnunn1/tilix) or [Tilix Website](https://gnunn1.github.io/tilix-web/) to use my theme and the ported themes or from one that provided by the other contributors. Other terminal wont work...
* Pick the one you like and Copy the theme *.json to...
```
~/.config/tilix/schemes/
```
* OR tap the ["Preview available themes"](Themes.md) and pick the one you like and copy/paste the commands below the "SS" to Tilix Terminal...ie (for Terminix Dark)
```
wget -qO $HOME"/.config/tilix/schemes/terminix-dark.json" https://git.io/v7QaK
```
* And finally apply via Tilix
```
Preferences/Default/Color/Color scheme
```


### Install All:
* If you need to install all the themes at once, you can download and run the following script:
```
link-to-the-script
```
* or simply run these commands:
```
wget -O /home/$USER https://link-to-the-script \
&& chmod +x /home/$USER/tilix-themes-install.sh \
&& /home/$USER/tilix-themes-install.sh
```

* do not forget to remove the script after completion:
```
rm  /home/$USER/tilix-themes-install.sh
```


### Uninstall:
* Just delete the theme *.json...you're good to go!


### Screenshot:
* You can also ["Preview available themes"](Themes.md) before installing... 


### Video:
* Watch themes in action [135 Linux Terminal Themes in 135 Seconds! | on Tilix! ](https://www.youtube.com/watch?v=GKyHf7byvlY)


# Credits:
* To All the original theme author(s)
* [Gerald Nunn aka gnunn1](https://github.com/gnunn1) the original author of [Tilix](https://github.com/gnunn1/tilix) for sharing his awesome work with us....
* Special thanks to [EliverLara](https://github.com/EliverLara) for the screenies and codes for downloading themes via terminal
* Other contributors ([justbur1](https://github.com/justbur) [casonadams](https://github.com/casonadams) [shanff](https://github.com/shanff) [PanagiotisS](https://github.com/shanff) [FreddieOliveira](https://github.com/FreddieOliveira) [Heziode](https://github.com/Heziode)) for adding moar themes or update some stuff
* Video courtesy of baby WOGUE
* Thanks and...you guys are awesome!!!!
