# Dotfiles: Desktop Green

## Main
![](https://i.imgur.com/OComdB2.jpg)

## Console Workflow
Just some nerdy console stuff. In truth in truth don't use cmus much on my desktop. 
![](https://i.imgur.com/0gqYYCX.png)

## Graphical Workflow
And that looks more like my usual workflow. Switching between QtCreator, Telegram and Clementine-oh-god-what-a-song-give-me-some-lyrics.
![](https://i.imgur.com/K6yc528.png)

## Some Info
#### Tray Icons
I used [hardcode-Tray](https://github.com/bilelmoussaoui/Hardcode-Tray) to change the icons and their colors to match the main theme. I used [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) icons.
![Tray Icons](https://i.imgur.com/HaJsNN5.png)
```
sudo -E hardcode-tray --size 24 --theme Papirus
```
`hardcode-Tray` provides some means to change the colors via comand line. I couldn't to that. I don't know why, but `--color` option didn't work for me. In truth I didn't spend much time on that and just changed the color of SVG files with text editor. I have my Papirus icons located in `/usr/share/icons/Papirus/24x24`.

#### Calendar 
I used [gsimplecal](https://github.com/dmedvinsky/gsimplecal) to show nice calendar window when clicking on date.

![Calendar](https://i.imgur.com/VSjCdXK.png)

#### Workspaces Icons
Hahaha, I just had some fun :D
![Workspaces](https://i.imgur.com/vtvfQpg.png)

When it was time to decide how to display my workspaces it turned out I had a lot of fonts installed. Accidentialy I fount these cuties with [gucharmap](https://wiki.gnome.org/Apps/Gucharmap). It told me thats `NotoEmoji Nerd Font Mono` is responsible for coalas and octobuses. This font can be found here among ton of other [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).

#### GTK Theme
To adjust the colors of graphical applications I used [oomox](https://github.com/themix-project/oomox). I changed some colors of Numix theme.
For example, Thunar now looks like this.
![Thunar](https://i.imgur.com/ZVb9u8e.png)
