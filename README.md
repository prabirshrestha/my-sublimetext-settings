## Installing on Mac

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
rm -rf User/
git clone git@github.com:prabirshrestha/my-sublimetext-settings.git User
```

**Symlink Sublime Text**

```bash
sudo ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /bin/subl
```

## Installing on Windows

```bat
cd %APPDATA%\Sublime Text 2\Packages
del /s User
rmdir User
git clone git@github.com:prabirshrestha/my-sublimetext-settings.git User
```

## Installing on Linux

### Installing SublimeText in Ubuntu

```sh
sudo add-apt-repository ppa:webupd8team/sublime-text-2
sudo apt-get update
sudo apt-get install sublime-text
sudo ln -s /usr/lib/sublime-text-2/sublime_text /usr/bin/subl
```

```sh
cd ~/.config/sublime-text-2/Packages
rm -rf User/
git clone git@github.com:prabirshrestha/my-sublimetext-settings.git User
```
