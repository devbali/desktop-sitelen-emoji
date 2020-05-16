# Sitelen Emoji Extensions for Desktop Users
Scripts to enable desktop users to type in Sitelen Emoji, using simple autocorrect style extensions

## Windows

## MacOS
- Download the macossitelenemoji.inputplugin file
- Double click it to make it run (You might have to give it some permissions in order to do so)
- There should be a "Sitelen Emoji" Keyboard in your list of installed keyboards
- To use it, switch to that keyboard and type, and switch back to your regular keyboard when needed

## Linux
- Check if Inteligent Input Bus (IBus) is installed and enabled on your machine (enter `ibus version` in the command line)
- If not, install by `sudo apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4 ibus-table`
- Download the linuxibus.txt file and run command `sudo ibus-table-createdb -n /usr/share/ibus-table/tables/sitelenemoji.db -s linuxibus.txt` from the same directory
- Now that the the extension has been installed, run `ibus-daemon -drx` or restart your machine
- This enables you to run `ibus-setup` to complete the setup. There should be an option for a "Sitelen Emoji" keyboard under "English (US)." Select and install the keyboard
- To use Sitelen Emoji, switch to that keyboard and type, and switch back to your regular keyboard when needed
