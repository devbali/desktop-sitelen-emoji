# Sitelen Emoji Extensions for Desktop Users
Scripts to enable desktop users to type in Sitelen Emoji, using simple autocorrect style extensions

## Windows
- Install AutoHotkey if not already installed [here](https://www.autohotkey.com/), and download this repository as a zip (and extract)
- Next, press `Windows+R` and enter `shell:startup` (`shell:common startup` for the extension to be available to all users). This will take you to a folder, where you can move/copy the `default.ahk` script from the Windows folder
- Now you can restart, and Sitelen Emoji is ready to use. It is off by default, but you can press `F1` or `Fn+F1` to turn it on or off again

## MacOS
- Download this repository as a zip (and extract)
- Double click the `default.inputplugin` script in the MacOSX folder to make it run (You might have to give it some permissions in order to do so)
- There should be a "Sitelen Emoji" Keyboard in your list of installed keyboards
- To use it, switch to that keyboard and type, and switch back to your regular keyboard when needed

## Linux
- Check if Inteligent Input Bus (IBus) is installed and enabled on your machine (enter `ibus version` in the command line)
- If not, install by `sudo apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4 ibus-table`
- Download this repository as a zip (and extract). Then run the command `sudo ibus-table-createdb -n /usr/share/ibus-table/tables/sitelenemoji.db -s Linux/default_ibus.txt` from the directory you extracted to
- Now that the the extension has been installed, run `ibus-daemon -drx` or restart your machine
- This enables you to run `ibus-setup` to complete the setup. There should be an option for a "Sitelen Emoji" keyboard under "English (US)." Select and install the keyboard
- To use Sitelen Emoji, switch to that keyboard and type, and switch back to your regular keyboard when needed


## Optional: Instructions to download a pu-only list or a nimi ale pona list
- The instructions below for each os use the "default" file for each OS
- However there are also "pu_only" and "nimi_ale_pona" files in each OS's directory
- The default file contains all pu words, and 16 non pu words in addition. These are words the vast majority of the toki pona user base are familiar with.
- There is the nimi ale pona list, that might suggest some very rare words, since it adds 39 words to the default list
- For pu-rists, there is a pu only list that will only recommend pu words to you
