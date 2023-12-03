# Git bash for Windows Powerline Theme

Light & simple powerline theme for Git bash for windows

![ScreenShot](ss.png)


## Pre-Requisites

* In order for this theme to render correctly, you will need a
[Powerline-patched font](https://github.com/powerline/fonts).


## Installation:

I recommend the following:

```bash
cd $HOME
mkdir -p .bash/themes/git_bash_windows_powerline
git clone https://github.com/dhwanish-3/git-bash-powerline-theme.git .bash/themes/git_bash_powerline_theme
```

then add the following to your .bashrc:

```bash
# Theme
THEME=$HOME/.bash/themes/git_bash_powerline_theme/theme.bash
if [ -f $THEME ]; then
   . $THEME
fi
unset THEME
```
