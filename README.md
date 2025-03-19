Update: 
* Removed the username@host in the prompt
* Change font color to black because it currently on dark themes it's not clearly visible.
* Updated the Install clone url (to share with someone)

# Git bash for windows powerline theme

Light & simple powerline theme for Git bash for windows

![image](https://github.com/user-attachments/assets/2cb61b65-2b7f-4466-9d91-e389acce20ad)

## Install:

I recommend the following:

```bash
cd $HOME
mkdir -p .bash/themes/git_bash_windows_powerline
git clone https://github.com/turchinc/git_bash_windows_powerline.git .bash/themes/git_bash_windows_powerline
```

then add the following to your .bashrc:

```bash
# Theme
THEME=$HOME/.bash/themes/git_bash_windows_powerline/theme.bash
if [ -f $THEME ]; then
   . $THEME
fi
unset THEME
```

## Requisites

* In order for this theme to render correctly, you will need a
[Powerline-patched font](https://github.com/powerline/fonts).

## License

MIT
