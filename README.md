Installing on Windows

```
cd %APPDATA%\Sublime Text 2\Packages
del /s User
rmdir User
git clone git@github.com:prabirshrestha/my-sublimetext-settings.git User
cd User
git submodule init
git submodule update
```
