<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-xfce-terminal/develop/src/assets/nord-xfce-terminal-banner.svg"/></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xfce-terminal/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-xfce-terminal.svg?style=flat-square&color=88C0D0&label=Release"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="http://docs.xfce.org/apps/terminal/start">XFCE Terminal</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xfce-terminal/develop/src/assets/scrot-colortest.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Getting started
### Installation
#### Manual
Copy the [`nord.theme`](https://github.com/arcticicestudio/nord-xfce-terminal/blob/develop/src/nord.theme) file to the local configuration directory `~/.local/share/xfce4/terminal/colorschemes`.

#### Install Script
The included `install.sh` shell script can be used for an automated installation.  
If no option is specified, the default theme file is `src/nord.theme`.

A list of available options can be shown with the `--help` option.
```shell
./install.sh --help
```
Syntax: `install.sh [OPTIONS]`

| Option | Description |
| --- | --- |
| `-h`, `--help` | Shows the help |
| `-v`, `--verbose` | Verbose output |
| `-t  <SCHEME_FILE>`, `--themefile <THEME_FILE>` | Use the specified theme file |

### Activation
  1. Open the *Edit* menu and select *Preferences*
  2. Switch to the *Colors* tab
  3. Select `Nord` from the *Presets* drop-down menu

![][scrot-readme-color-preset]

## Screenshots
<p align="center"><strong>htop</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xfce-terminal/develop/src/assets/scrot-htop.png"/></p>

## Development
[![](https://img.shields.io/badge/Changelog-0.1.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-xfce-terminal/blob/v0.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-xfce-terminal/issues).

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/nord/repository-footer-separator.svg?sanitize=true" /></p>

<p align="center">Copyright &copy; 2016-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xfce-terminal/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>

[scrot-readme-color-preset]: https://raw.githubusercontent.com/arcticicestudio/nord-xfce-terminal/develop/src/assets/scrot-readme-color-preset.png
