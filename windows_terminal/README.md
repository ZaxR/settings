The settings.json file programatically defines settings for Windows Terminal.
This file can be located in one of a few different locations,
but is most typically `%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json`.
See https://docs.microsoft.com/en-us/windows/terminal/install#settings-json-file for more details.

If you wish to use a custom background, make sure to update "backgroundImage" key in profiles.lists.
Background images must be located in a mounted folder, such as your user folder.
Example:
```sh
# Install ubuntu backgrounds
sudo apt-get install ubuntu-wallpapers-focal
# Then copy backgrounds into a usable location:
cp /usr/share/backgrounds/* /mnt/c/Users/zaxr/Documents/.
```
