<p align="center">
<a href="https://axyl-os.github.io" target="_blank"><img src="https://avatars.githubusercontent.com/u/91398141?s=200&v=4"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-Green?style=flat-square">
  <img src="https://img.shields.io/github/downloads/axyl-os/axyl-iso/total?label=downloads&logo=github&color=blue&style=flat-square">
  <img src="https://img.shields.io/github/stars/axyl-os/axyl-iso?style=flat-square">
  <img src="https://img.shields.io/github/issues/axyl-os/axyl-iso?color=violet&style=flat-square">
</p>

## Table of Contents

- [About ⁉️](#about)
- [Gallery 📷](#gal)
- [Global Keybinds ✍️](#keybinds)
    - [dwm Keybinds](#dwmkeys)
    - [Qtile Keybinds](#qtilekeys)
- [How To Install ⁉️](#install)


<a id="about"></a>
A minimal Arch-based GNU/Linux Distribution


<a id="gal"></a>
## Gallery 📷
![img](https://cdn.discordapp.com/attachments/891886464013566012/893031310786961438/Screenshot_2021-09-30-02-58-01_3840x1080.png)
![img](https://cdn.discordapp.com/attachments/891886464013566012/893031318315737118/Screenshot_2021-09-30-02-58-23_3840x1080.png)
![img](https://cdn.discordapp.com/attachments/891886464013566012/893031321234976788/Screenshot_2021-09-30-02-59-53_3840x1080.png)


<a id="keybinds"></a>
## Global Keybinds ✍️

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `S + [1..7]`           | Switches to Workspace 1 to 7             |
| `S + Shft + [1..7]`    | Move Apps/Windows to Workspace 1 to 7    |
| `S + Enter`            | Launch Terminal (Alacritty)              |
| `S + C`                | Close window                             |
| `S`                    | Launch j4-dmenu-desktop                  |
| `S + D`                | Launch dmenu                             |
| `S + N`                | Launch NetworkManager dmenu              |
| `Alt + E`              | Launch Edit Configs dmenu                |
| `Alt + L`              | Launch Quick Links dmenu                 |
| `Ctrl + Alt + L`       | Lock Screen                              |
| `S + Shft + W`         | Launch Firefox                           |
| `S + Shft + F`         | Launch Thunar                            |
| `S + Shft + R`         | Ranger Quick Launch                      |


<a id="dwmkeys"></a>
## dwm Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `S + B`                | Toggle Bar                               |
| `S + [J,K]`            | Focus Next/Previous Client               |
| `S + [H,L]`            | Set Stack Size                           |
| `S + [T,F,M]`          | Set Client Layout to [Tiled,Floating,Monocle]|
| `S + Space`            | Cycle Layouts                            |
| `S + Shft + Space`     | Toggle Floating                          |


<a id="qtilekeys"></a>
## Qtile Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + R`      | Reload Qtile                             |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `S + [H,L,J,K]`        | Switch Focus to [Left,Down,Right,Up]     |
| `S + Shft + [H,L,J,K]` | Move Windows to [Left,Down,Right,Up]     |
| `S + Ctrl + [H,L,J,K]` | Grow Apps/Windows                        |
| `S + Shft + Enter`     | Toggle Split & Unsplit Sides of Stack    |
| `S + Tab`              | Toggle Between Layouts                   |


<a id="install"></a>
## Installation
Once you boot up Axyl and entered dwm desktop, you can start the 
Calamares installer by launching `dmenu` by hitting: `Superkey + D` 
on your keyboard and type in: `calinstall`
