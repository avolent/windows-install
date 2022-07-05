# Winget Install File
## Winget Installation
1. Go to microsoft store.
2. Search and install "App Installer"
3. Confirm the command `winget` works in the terminal.

## Program installations
To install all the applications run the following command in the directory of applications.json

```winget import --import-file "applications.json"``` 

After installing the files you can use the following command provided by Chris at https://christitus.com/windows-tool/

```iwr -useb https://christitus.com/win | iex```

Use this to remove all privacy exploits