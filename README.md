![logo](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/ts-logo.png) <br />

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-blueviolet?style=flat-square">
  <img src="https://img.shields.io/github/license/adi1090x/termite-style?style=flat-square">
  <img src="https://img.shields.io/github/stars/adi1090x/termite-style?color=red&style=flat-square">
  <img src="https://img.shields.io/github/forks/adi1090x/termite-style?style=flat-square">
  <img src="https://img.shields.io/github/issues/adi1090x/termite-style?style=flat-square">
</p>

A Simple Program To Change Colors And Fonts Of Termite In Real Time. <br />

### How to install

Follow the steps below - 

```bash
# go to home dir - 
cd $HOME

# clone this repository - 
git clone https://github.com/adi1090x/termite-style

# change to kitty-cat dir -
cd termite-style

# to install it, run -
./install

# And Follow the steps, it'll be installed on your system.
```
### Run

Run `termite-style` & select the right option -

```bash
$ termite-style

    ┌──────────────────────────────────────────────────────┐
    │░░░▀█▀░█▀▀░█▀▄░█▄█░▀█▀░▀█▀░█▀▀░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░░░█░░█▀▀░█▀▄░█░█░░█░░░█░░█▀▀░░░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░░▀░░▀▀▀░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────────┘
    [*] By- Aditya Shakya // adi1090x


    [C] Colors
    [F] Fonts
    [R] Random
    [I] Import
    [A] About 
    [Q] Quit

    [Select Option]: 
```
### Features

+ 90 popular colorschemes.
+ 20 powerline patched fonts.
+ Randomely change colorschemes.
+ Import colorschemes from *local file* and *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: i

    [P] PATH (Local File)
    [U] URL (Internet File)

    [Choose]: U

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/adi1090x/tRandomizer/master/colors/110.color
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (ie - `/home/aditya/dracula.config`) of the colorscheme file.
+ To import *web file*, enter the file url (ie - `https://raw.githubusercontent.com/adi1090x/tRandomizer/master/colors/100.color`) of the colorscheme file.
+ You can generate color schemes from [terminal.sexy](https://terminal.sexy/) and export it to a file in termite format, then import it in `termite-style`.
+ I've already generated 500 random color-schemes from *terminal.sexy*, which you can get [here](https://github.com/adi1090x/tRandomizer/tree/master/colors), just copy the ***[raw file url](https://raw.githubusercontent.com/adi1090x/tRandomizer/master/colors/121.color)*** and paste it in `termite-style`.

## Color Schemes Previews

![preview1](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_nord.png) <br />

![preview2](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_material.png) <br />

![preview3](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_dracula.png) <br />

![preview4](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_rydgel.png) <br />

![preview5](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_wildc.png) <br />

![preview6](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_zenburn.png) <br />

![preview7](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/preview_wob.png) <br />

There are total ***90 color-schemes*** including black-on-white, dracula, gnometerm, gotham, gruvbox-dark, gruvbox-light, material, nancy, neon, nord, rydgel, smyck, solarized-dark, solarized-light, tomorrow-night, white-on-black, wild-cherry, zenburn, etc... <br />

## Fonts Previews

![preview1](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_1.png) <br />

![preview2](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_2.png) <br />

![preview3](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_3.png) <br />

![preview4](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_4.png) <br />

![preview5](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_5.png) <br />

![preview6](https://raw.githubusercontent.com/adi1090x/termite-style/master/previews/font_6.png) <br />

There are total ***20 Powerline Patched Fonts*** including Anonymous-Pro, Courier-Prime, DejaVu, Fantasque, FiraCode, Fira, GNU-FreeFont, Go-font, Hack, Hermit, Inconsolata, Iosevka, LiberationMono, Meslo, Monofur, Monoid, OpenDyslexic, Roboto, Source-Code-Pro, Ubuntu. <br />

### FYI

- This note is for people with *weak heart*, the setup file will need the **sudo** permission, because this program puts colors and fonts files inside the *"/usr/share"* directory. So, before asking me "why dafuq this need sudo?"... **Read the code.**
- That's All Guys... Have Fun, Enjoy.
