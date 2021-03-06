![alt tag](https://github.com/daniruiz/Flat-Remix-GNOME-theme/blob/master/Images/logo.png?raw=true)

###### Flat-Remix is licensed under the Creative Commons Attribution Share Alike 4.0
<hr>
<br>

Flat Remix GNOME theme is a pretty simple shell theme inspired on material design. It follows a modern design using "flat" colors with high contrasts and sharp borders.

<br/>

# Screenshots

#### Flat Remix
![Screenshot Flat-Remix](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/1.png)
#### Flat Remix Dark
![Screenshot Flat-Remix-Dark](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/2.png)
#### Flat Remix Darkest
![Screenshot Flat-Remix-Darkest](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/3.png)
#### Flat Remix Miami
![Screenshot Flat-Remix-Miami](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/4.png)
#### Flat Remix Dark Miami
![Screenshot Flat Remix-Miami-Dark](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/5.png)
#### Login Screen
![Screenshot Flat Remix login](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/gdm.png)


# Installation

#### Manual installation

1. Download and uncompress the zip file.  
1. Move "Flat-Remix" folder to ".themes" in your home directory.  
1. Install [user themes extension](https://extensions.gnome.org/extension/19/user-themes/)  
1. To set the theme, run the following command in terminal:  
`gsettings set org.gnome.shell.extensions.user-theme name "Flat-Remix"`  
or select "Flat-Remix" via gnome-tweaks.  

#### Terminal installation

```sh
cd /tmp && rm -rf flat-remix-gnome &&
git clone https://github.com/daniruiz/flat-remix-gnome && cd flat-remix-gnome &&
sudo make install

sudo mv /usr/share/gnome-shell/gnome-shell-theme.gresource /usr/share/gnome-shell/gnome-shell-theme.gresource.old &&
sudo ln /usr/share/themes/Flat-Remix/gnome-shell-theme.gresource /usr/share/gnome-shell/gnome-shell-theme.gresource
```

#### Ubuntu based distributions:

```sh
sudo add-apt-repository ppa:daniruiz/flat-remix
sudo apt-get update
sudo apt-get install flat-remix-gnome
```

##### Fedora based distributions

```sh
sudo dnf copr enable daniruiz/flat-remix
sudo dnf install flat-remix-gnome
```

##### Arch based distributions
+ [`flat-remix-gnome-git`](https://aur.archlinux.org/packages/flat-remix-gnome-git/) (AUR)

<br/>
<hr>
<p align="center">
<img src="https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/gdm-session-selector.jpg">
</p>

# [Flat Remix ICON theme](https://github.com/daniruiz/Flat-Remix/)  

<p align="center">
<img src="https://raw.githubusercontent.com/daniruiz/Flat-Remix/master/preview.png">
</p>

<br/>

# [Flat Remix GTK theme](https://github.com/daniruiz/flat-remix-gtk)
![Flat Remix icon theme perview](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GTK/master/1.png)


# Donate

You can also support the development of Flat Remix by donating  

- [![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7LEWLS78EAJGJ)

- Bitcoin Wallet:  
`1K4RhLu7u5xGheWrLAnMPhF2mTA7oMCMj4`  
  
- Monero Wallet:   `46o1H6xAnvNY25N1rosd9oUcN2pxhYaErU9qc48VwDNf3xrzSWhqWC5WbwaVe4vUMveKAzAiA4j8xgUi29TpKXpm3zCs4zx`  
