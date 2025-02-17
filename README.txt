This folder stores all of your Anki data in a single location,
to make backups easy. To tell Anki to use a different location,
please see:

Locations:
    - Windows: %APPDATA%\Anki2
    - MacOS: ~/Library/Application\ Support/Anki2
    - Linux: ~/.local/share/Anki2

https://docs.ankiweb.net/files#startup-options

# NOTE: if you add your own flashcards or decks to your instance of anki, they will be deleted after cloning this directory.
Make sure that whatever you add, you export your added decks and save them to a location outside of this directory

## How to get these flashcards to your system:

### Pre-requisites

Make sure you have git installed on your machine and can use a terminal or git bash.

https://git-scm.com/downloads

Also, make sure you have anki installed on your system

### Installing

cd to the configuration directory listed in the locations above. 

click on code above, copy the link and paste it to the command below.

run 
```bash
git clone <URL>
```
Open you anki application and you should be able to see the latest cards stored.
