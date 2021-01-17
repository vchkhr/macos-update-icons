# macOS Icons Updater
macOS Icons Updater tool automatically replaces custom icons after software updates.

## Problem
After updating applications, custom icons for programs are replaced with standard ones. Replacing requires a lot of repetitive steps.

## Solution
Just put custom icons in the specific folder and run this tool after each update of the software. It will automatically replace all the custom icons.

## How to Use
1. Download the tool.\
Click `Code`, `Download zip` and unarchive `macos-icons-updater.sh` file.
2. Put all the custom icons in the same folder with the tool.\
Rename icons as programs named in the Dock.\
Do not remove `.icns` extension.\
Do not keep other files in this folder.\
For example, you have created the folder `icons` in the `Downloads`. It will have a structure like this:
```
Firefox.icns
GitHub Desktop.icns
macos-icons-updater.sh
Microsoft Word.icns
TeamViewer.icns
```
3. Navigate to the tool in Terminal.\
Open Terminal (press <kbd>command</kbd>+<kbd>space</kbd>, paste `Terminal` and press <kbd>enter</kbd>) and navigate to the folder where you keep the icons and tool. In the example, paste `cd Downloads/icons` and press <kbd>enter</kbd>.
4. Run the tool.\
Paste `zsh macos-icons-updater.sh` into the Terminal and press <kbd>enter</kbd>.\
If you are not logged in with an administrator account or don't know a password, paste `zsh macos-icons-updater.sh -nosudo` and press <kbd>enter</kbd>.
5. Icons will be replaced with the new ones, Dock and Finder will be restarted.\

You may need to launch the program before the Dock icon refreshes.

## Feedback
Feedback is always welcome at [GitHub Issues](https://github.com/vchkhr/macos-icons-updater/issues).

## Support
<a href="https://www.buymeacoffee.com/vchkhr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="60px" width="217px"></a>

