# bash-prompt-simple
Simple bash prompt in a single file that can be downloaded, used as is or tweaked, and sourced. This is a highly modified version of a fork of a fork.

* Supports:
  * GIT   (*branch*)
  * AWS   (*profile & region*)
  * Kubernetes   (*context & namespace*)
  * Python   (*virtual env*)
  * NerdFonts   (*pre-selected icons that can be changed*)
  * Multiple Color Schemes   (*a primary color and secondary color*)

## Installation
To enable, just add to your **.bash_profile** or **.bashrc** with the following:
```sh
if [ -f "$HOME"/.bash_prompt ]; then
    source "$HOME"/.bash_prompt
fi
```

### Installation of a NerdFont on MacBookPro (Optional):
This enables fancy icons:
1. Go to [NerdFonts](https://www.nerdfonts.com/font-downloads)
1. In a termporary donwload directory. Download a Font. I prefer Sauce Code Pro.
1. Unzip, and move **Sauce Code Pro Nerd Font Complete Mono.ttf** to $HOME/Library/Fonts 
    ```sh
    mv "Sauce Code Pro Nerd Font Complete Mono.ttf" $HOME/Library/Fonts
    ```
1. Open Iterm2, then go to *Iterm2* on the top bar and select **Prefrences**.
1. Go to **Profiles** on the top and click on the **Font** drop down and select Sauce Code Font.
1. Set **symbols_on** to **true** in **.bash_prompt**
1. Launch a new terminal and should be good to go.

### Installation of a NerdFont on Linux (Optional):
1. Go to [NerdFonts](https://www.nerdfonts.com/font-downloads)
1. In a termporary donwload directory. Download a Font. I prefer Sauce Code Pro.
1. Unzip, and move **Sauce Code Pro Nerd Font Complete Mono.ttf** to **$HOME/.fonts** 
    ```sh
    mkdir -p $HOME/.fonts
    cp "Sauce Code Pro Nerd Font Complete Mono.ttf" $HOME/.fonts
    ```
1. Open your terminal and point to new font.
1. You may need to set the font option **Allow selection of variable-pitched fonts**
1. Set **symbols_on** to **true** in **.bash_prompt**
1. Launch a new terminal and should be good to go.

## Selecting prompt color scheme:
* Set your **theme_color_primary** and **theme_color_secondary** in **.bash_prompt**

## Screenhots of your prompt
* [Post a screenshot](https://github.com/bytebeast/bash-prompt-simple/discussions/3) of the colors you picked or the fork you tweaked. 


**Star** or **Fork** it if you like it.




