![Pinky](https://i.imgur.com/zTMr1qZ.png)

# Dribbble-Pinky
### [Spicetify](https://github.com/khanhas/spicetify-cli)

### [Original theme](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish)

### Pinky is pink color scheme for Dribbble spicetify theme, if you want to help me and improve this color cheme please contact me (Да#4103)

## Screenshots:

![lt](https://i.imgur.com/2gfASDn.png)
![dt](https://i.imgur.com/lX6hs49.png)

## Installation:
Open command prompt or whatever, and copy&paste the following command:
```
cd .spicetify\Themes && git clone https://github.com/ccrashtek/Dribbble-Pinky
```
after that, you need to install dribbblish extension:

### Windows
In Powershell:
```powershell
cd "$(spicetify -c | Split-Path)\Themes\Dribbble-Pinky"
Copy-Item dribbblish.js ..\..\Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbble-Pinky color_scheme base
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

### Linux and MacOS:
In Bash:
```bash
cd "$(dirname "$(spicetify -c)")/Themes/Dribbble-Pinky"
cp dribbblish.js ../../Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbble-Pinky color_scheme base
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```
![](https://i.imgur.com/8Qd0O2q.png)
After installation you need to go to spotify directory, create shortcut for ```Spotify.exe``` and write ```--transparent-window-controls``` after "Target" path
You can also apply icon by going to shortcut properties and clicking "Change Icon"

## Customization:
You can simply customize your color_cheme by changing colors in ```color.ini``` file.
Default theme is white, you can change it do dark by typing the following command:
```
spicetify config color_scheme dark
```
and to change it back to white:
```
spicetify config color_scheme white
```

### Happy new year @everyone!

#### [:black_heart:](https://youtu.be/_ygcbrBRMLY)
