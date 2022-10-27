# local-backuper
This is a simple utility for backuping all important files to a seperate location, like an USB stick.

You can organize files and folders in a yml-dict and then copy them at once to a specified location.

## How to use
When you run `LocalBackupManager.py` a dialog asks you for the filepath of the yml file. You need to create one manually.
![initial dialog](/assets/initQT.png)

In the main interface, you can add files and folders to the list which is rendered below. To remove a file or folder from the list, just select it again.
You can exclude certain files in a folder from being copied by appending them to the "blacklist".
![main interface](/assets/mainQT.png)

After you selected a backup destination you can start the copying process, given that there's enough space. It can take a long time!


## Misc
In `LocalBackupManager.py`, you can specify `DEFAULT_YML_PATH_IN_BOX` and `DEFAULT_YML_PATHS` for convenience.

There's surely a lot of bugs and weird behavious, but for my purposes it works. 
