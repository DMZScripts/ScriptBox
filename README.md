
Documentation
===
![Script Box](https://github.com/DMZScripts/Script-Box/blob/9f4f8e929afca237b01dc5d5874088f371159d23/images/Script%20Box_003.png?raw=true)
Dynamic Maxscript Dialog for 3ds Max

Table of content
---
- [Description](#description)
  - [Features](#features)
- [UI](#ui)
  - [Dialog Options](#options)
  - [Load Folders](#folders)
  - [Script Menu](#scripts)
<br></br>
## Description<a name="description"></a>
Script Box is a tool  for 3ds Max that streamline the process of installing and executing Maxscripts by allowing users to select any folder and generate a dynamic dialog menu.
### Features <a name="features"></a>
- Dynamic and dockable interface
- Multi-threaded script loading
- Include sub-folders
- Grouped by macroScript, plugin, utility and standard.
- Extended Tooltip information
- Open MaxScripts in the Scripting editor
<br></br>
## UI <a name="ui"></a>
### Dialog Options <a name="options"></a>
![Dialog Options](https://github.com/DMZScripts/Script-Box/blob/d9e91be4cf9fe430b84487f17de7807e740de224/images/UI_DialogOptions_001.png?raw=true)
- **Installer**: Opens the Script Box installer
- **DockLeft**: Docks the dialog menu left
- **Float/Window**: Switches the dialog menu between floatable and menu mode
- **DockRight**: Docks the dialog menu right
- **Close**: Close the menu

### Load Folders <a name="folders"></a>
![Load Folders](https://github.com/DMZScripts/Script-Box/blob/d9e91be4cf9fe430b84487f17de7807e740de224/images/UI_Folders_001.png?raw=true)
- **Select Folder**: Loads a new folder. Removes previous loaded folders.
- **Add Folder**: Add a new folder and re-loads all folders in the Folders list.
- **Include sub-folders**: Include all sub-folders when loading the currently selected folder in the Folder list. Sub-folders called *_archive* are ignored in the search.
- **Remove Sub-Folders**: Ignore all sub-folders from being loaded, for the currently selected folder.
- **Remove Folder**: Remove selected folder from Folders list. Re-load remaining folders.
- **Reload all Folders**: Re-load all folder in Folder list.

### Script Menu <a name="scripts"></a>
![Script Menu](https://github.com/DMZScripts/Script-Box/blob/d9e91be4cf9fe430b84487f17de7807e740de224/images/UI_ScriptMenu_001.png?raw=true)
>All collected script files are scanned for macroScripts, plugins and utility classes.  Each instance of these classes gets a button that executes only that part of the script. The buttons are grouped according to these script classes.
If no class instance can be found, the script is interpreteded as regular maxScript and receives a single button.

- **Dialog titel**: Shows the name of the loaded folder. *(.../Object Creation)*
- **Open Folder**: Opens the folder in windows Explorer
- **Folder Path**: Full folder path. Read-only.
- **Open Script**: Opens the script file in the Scripting Editor.
- **Launch Button**: Executes the script.
<br></br>
