# WDD-locale
Translation files for WinDynamicDesktop

# This repo has been archived. Translations are now hosted on [POEditor](https://poeditor.com/join/project/DEgfVpyuiK). More details can be found [here](https://github.com/t1m0thyj/WinDynamicDesktop/wiki/Translating-the-app).

## Creating New Translation

* Download the latest `messages.pot` file from [here](https://github.com/t1m0thyj/WDD-locale/blob/master/messages.pot)
* Download and install the free program [PoEdit](https://poedit.net/)
* Launch PoEdit and click the "Create new translation" button, then select the `messages.pot` file
* Go through the list of messages and translate each one
* Save your translation to a `.po` file (an `.mo` file will also automatically be generated)
* Copy the `.mo` file to the same folder as the app EXE (see [here](https://github.com/t1m0thyj/WinDynamicDesktop/wiki/Troubleshooting#finding-where-app-is-installed) if you don't know where that is)
* Close WinDynamicDesktop if it's running and edit the `settings.conf` file and change `language=null` to `language="{LANGUAGE_NAME}"` where `{LANGUAGE_NAME}` is the name of the `.mo` file (`{LANGUAGE_NAME}.mo`)
* Restart the app and you should see your translation
* Upload the `.po` file (not `.mo`) on GitHub (you may need to change the file extension to `.txt` since it seems like GitHub doesn't support uploading `.po` files)

## Updating Existing Translation

* Download the latest `messages.pot` from [here](https://github.com/t1m0thyj/WDD-locale/blob/master/messages.pot)
* Open the `.po` file for your translation in PoEdit
* Select `Update from POT file...` from the `Catalog` menu and navigate to `messages.pot` in the file dialog
* Look for any missing or outdated translations and fix them
* Upload the `.po` file (not `.mo`) on GitHub (you may need to change the file extension to `.txt` since it seems like GitHub doesn't support uploading `.po` files)
