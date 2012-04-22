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
