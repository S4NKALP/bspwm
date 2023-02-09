<!-- HEADERS -->
<p align="center">
  <b> ~ Sankalp's configuration files ~ </b>
</p>



<!-- INFORMATION -->


<img src="https://raw.githubusercontent.com/S4NKALP/bspwm/main/TokyoNight.png" alt="img" align="right" width="400px">

This is my personal collection of configuration files.

You are probably here for my **Aesthetic BSPWM** configuration.

The [setup section](#setup) will guide you through the installation process.

Here are some details about my setup:

- **WM:** [bspwm](https://github.com/baskerville/bspwm)
- **OS:** [Arch Linux](https://archlinux.org)
- **Terminal:** [kitty](https://github.com/kovidgoyal/kitty)
- **Shell:** [zsh](https://wiki.archlinux.org/index.php/Zsh)
- **Widgets:** [eww](https://github.com/elkowar/eww)
- **Compositor:** [picom](https://github.com/ibhagwan/picom)
- **Editor:** [neovim](https://github.com/neovim/neovim)
- **Browser:** [firefox](https://www.mozilla.org/en-US/firefox)
- **File Manager:** [thunar](https://github.com/xfce-mirror/thunar)
- **Application Launcher:** [rofi](https://github.com/davatorium/rofi)

---

<!-- SETUP -->

## Setup.

> This is step-by-step how to install these bspwm dotfiles. Just [R.T.F.M](https://en.wikipedia.org/wiki/RTFM).

### Installation (Manual)

> After cloning the repository, install the necessary dependencies to replicate by setup.

   <details open>
   <summary><strong>Arch Linux (and Arch-based distributions)</strong></summary>

> Assuming your **AUR Helper** is [yay](https://github.com/Jguer/yay).

```sh
 $ yay -S bspwm sxhkd rofi kitty picom-ibhagwan-git calcurse todotxt \
 feh jq dunst betterlockscreen brightnessctl playerctl maim \
 xclip imagemagick

```

   </details>

   <br>

> Then after the dependencies are installed, copy the files to it's respective folders.

   <details open>
   <summary><strong>Config and Binaries</strong></summary>

```sh
 $ mkdir -p $HOME/.config/ && cp -r ./config/* $HOME/.config/
 $ mkdir -p $HOME/.local/bin/ && cp -r ./bin/* $HOME/.local/bin/
 $ cp -r ./misc/* $HOME/
```

   </details>

   <br>

> You will need to install a few fonts.

- **Cartograph CF:** [here](https://en.bestfonts.pro/font/cartograph-cf)
- **JetBrainsMono NF:** [here](https://github.com/ryanoasis/nerd-fonts)
- **Font Awesome:** [here](https://fontawesome.com/download)
- **Comic Mono :** [here](https://dtinth.github.io/comic-mono-font/)

   <br>

> Once finished copying the files, you might want to finalize the changes to your system.

```sh
 # Rebuilds the font cache
 $ fc-cache -fv
```

   <br>

> Lastly, log out from your current desktop session and log in into bspwm.

   <br>

## Miscellaneous.

- **GTK Theme**

  > You can find TokyoNight GTK theme [here](https://github.com/koiosdev/Tokyo-Night-Linux/tree/master/usr/share/themes/TokyoNight).

- **Icon Theme <kbd>Suggested</kbd>**
  > You can install [this](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) icon theme that suits the GTK theme.
  
  > 
