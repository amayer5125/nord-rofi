# Nord Rofi Theme

A [Rofi](https://github.com/davatorium/rofi) theme based on [Nord](https://github.com/arcticicestudio/nord) theme by Arctic Ice Studio

![Screenshot of Rofi with Nord Theme](screenshot.jpg)

## Getting Started

### Installation

Copy nord.rasi to the rofi configuration directory at ~/.config/rofi/.

```
curl -o ~/.config/rofi/nord.rasi https://raw.githubusercontent.com/amayer5125/nord-rofi/master/nord.rasi
```

Then add the following line to your [rofi configuration](https://github.com/davatorium/rofi/wiki/Configuring-Rofi) file, usually located at ~/.config/rofi/config.rasi.

```
theme: "nord";
```

### Optional

Download and add [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed) font to rofi configuration file.

```
font: "Roboto Condensed 16";
```

Other recomendations are, changing the default width and moving rofi to the top of the screen.

```
width: 33;
location: 2;
```
