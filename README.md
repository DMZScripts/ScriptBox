
Documentation
===
![Script Box](https://github.com/DMZScripts/Script-Box/blob/9f4f8e929afca237b01dc5d5874088f371159d23/images/Script%20Box_003.png?raw=true)

Table of contents
---
- [Description](#description)
  - [Features](#features)
  - [Support](#support)
- [UI](#ui)
  - [Dialog Options](#options)
  - [Load Folders](#folders)
  - [Script Menu](#scripts)
<br></br>
## Description<a name="description"></a>
Script Box is a tool for 3ds Max that streamline the process of installing and executing Maxscripts by allowing users to select any folder and generate a dynamic dialog menu.
It allows the user to organize macroScripts, plugins, utilities and regular scripts within 3ds Max, without requiring users to navigate through complex procedures.

### Features <a name="features"></a>
- Execute buttons for every Maxscript
- Multi-threaded script loading
- Include sub-folders
- Grouped by macroScript, plugin, utility and standard.
- Dynamic, dockable and resizeable interface
- Extended Tooltip information
- Open MaxScripts in the Scripting editor

### Support <a name="support"></a>
- 3ds Max 2021-2024
- .ms, .mse, .mcr files
- macroScripts, plugin, utility classes
<br></br>
## UI <a name="ui"></a>
### Dialog Options <a name="options"></a>
![Dialog Options](https://github.com/DMZScripts/Script-Box/blob/1cd9f2b20036a6cdf2430db8deef4ba194f3bdce/images/UI_DialogOptions_002.png?raw=true)
- **Installer**: Opens the Script Box installer
- **DockLeft**: Docks the dialog menu left
- **Float/Window**: Switches the dialog menu between floatable and menu mode
- **DockRight**: Docks the dialog menu right
- **Close**: Close the menu

### Load Folders <a name="folders"></a>
![Load Folders](https://github.com/DMZScripts/Script-Box/blob/4a027458d260b2677e0ae19d412362bf1ca73cfa/images/UI_Folders_002.png?raw=true)
- **Select Folder**: Loads a new folder. Removes previous loaded folders.
- **Add Folder**: Add a new folder and re-loads all folders in the Folders list.
- **Include Sub-Folders**: Include sub-folder hierarchy for the currently selected folder. Exclude folders named *_archive*
- **Remove Sub-Folders**: Ignore sub-folders from being loaded for the currently selected folder.
- **Remove Folder**: Remove currently selected folder from Folders list. Re-load remaining folders.
- **Reload all Folders**: Re-load all folders in the Folder list.
- **Folder List**: Select a folder to *Include/Remove Sub-Folders* or *Remove Folder*.

### Script Menu <a name="scripts"></a>
![Script Menu](https://github.com/DMZScripts/Script-Box/blob/1cd9f2b20036a6cdf2430db8deef4ba194f3bdce/images/UI_ScriptMenu_002.png?raw=true)
>All collected script files are scanned for macroScripts, plugins and utility classes.  Each instance of these classes gets a button that executes only that part of the script. The buttons are grouped according to these script classes.
If no class instance can be found, the script is interpreted as regular maxScript and receives a single button.

- **Dialog title**: Shows the name of the loaded folder. *(.../Object Creation)*
- **Open Folder**: Opens the folder in windows Explorer
- **Folder Path**: Full folder path. Read-only.
- **Open Script**: Opens the script file in the Scripting Editor.
- **Launch Button**: Executes the script.
<br></br>
