# Chicago95Solarized

<p> Hello! I created this spin of the theme based on an r/unixporn post you can find <a href="https://www.reddit.com/r/unixporn/comments/nv2rpv/xfce_all_things_solarized/">here</a>. Neither Chicago95 nor the idea from the post is mine, however, the OP seems to have gone offline for a few months, and their google drive link is broken. In other words, I take no credit for any of this! I may add some more pics of the solarized version along with a more updated readme at some point, but I basically just went into the css files and referenced the hex codes with ones from the solarized color scheme. Hopefully this helps others who were struggling with updating the theme.</p>

#### XFCE / Xubuntu Windows 95 Total Conversion

<p align="center">
<img src="Screenshots/Chicago95_Desktop.png" alt="Chicago95 Desktop"/>
</p>

*Click [here](Screenshots/SCREENSHOTS.md) for more screenshots*

I was unhappy with the various XFCE/GTK2/GTK3 Windows 95 based themes and decided to make one that was more consistent across the board for theming.

#### Included in this theme:

- New icons to complete the icon theme started with Classic95
- GTK2 and GTK3 themes
- Edited Redmond XFWM theme to more accurately reflect Windows 95
- Chicago95 Plus! A tool to preview and install Windows 95/98/ME/XP themes
- Plymouth theme created from scratch
- An MS-DOS inspired theme for oh-my-zsh
- Partial support for HiDPI monitors
- Partial icon theme for Libre Office 6+

#### Requirements

GTK+ 3.22 or 3.24

Xfce 4.12 or 4.14

gtk2-engines-pixbuf

A Window compositor

(If your are using an older desktop that uses GTK3.18, you can use [this forked version of the theme.](https://github.com/EMH-Mark-I/Chicago95-Custom-XUbuntu-16.04-))

-----

## Documentation

[Click here](INSTALL.md) for Chicago95 documentation and extra features.

-----

## Installation

### Packages

|Distro|Package Name/Link|
|:----:|:----:|
| Debian 9 | [obs-repo] |
| Debian 10 | [obs-repo] |
| Debian Testing/Unstable | [obs-repo] |
| Ubuntu 18.04 - 20.04 | [obs-repo] |

### Manual installation and setup instructions
[Click here](INSTALL.md) for install steps.

### Install a Microsoft Windows Plus! theme
[Click here](Plus/README.MD) for installing custom themes.

### Install the Plymouth boot splash theme
[Click here](Plymouth/) for install steps.

### Install the Libre Office icon theme
[Click here](Extras/libreoffice-chicago95-iconset/README.md) for installing the Libre Office Chicago95 icon theme.

## KDE Support (experimental)
- SDDM Logon Manager:: Click `Install from file...` in Loggin Screen (SDDM) manager. Select `SDDM/Chicago95.tar.gz` to install the theme. 
- Splash Screen: `plasmapkg2 -t lookandfeel -i KDE/Splash/chicago95.splashscreen`

### Screenshots
[Click here to view screenshots](Screenshots/SCREENSHOTS.md)


### Code and license
License: GPL-3.0+/MIT

[obs-repo]: https://software.opensuse.org//download.html?project=home%3Abgstack15%3AChicago95&package=chicago95-theme-all
