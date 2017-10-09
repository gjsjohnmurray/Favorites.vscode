# Favorites - VSCode Extension

Manage and quickly access frequently used files. 
<hr/>

This simple extension allows in adding, removing and managing documents in the globally maintained "Favorites" list. 

This extensions is similar to other plugins of the "Favorites" family. Though  apart from traditional item context menu and buttons this plugin offers an extremely simple and intuitive way of structuring your favorites. The items definition is just a text document that can be freely edited and the changes reflected in the VSCode panel automatically after saving the file.

The functionality is self explanatory and includes following features:

* The items can be either files or folders
* Opening document or folder by clicking the item in the _Favorites_ list.
* Adding active document to _Favorites_ via the dedicated toolbar button.
* Removing active document from _Favorites_ via the item context menu.
* Refreshing (reloading) _Favorites_ via the dedicated toolbar button.
* Moving items up and down in the list
* Managing (edit) _Favorites_ list directly in _VSCode_. Once the _Favorites_ list definition is edited and saved the changes are automatically reflected in the _Favorites_ panel.

![image](https://raw.githubusercontent.com/oleg-shilo/Favorites.vscode/master/resources/images/favorites_vscode.gif)

Note: by default VSCode opens any file clicked from the  _Favorites_ list in the so called "preview mode". Thus the document tabs are reused and every new file is opened in the same tab. If you prefer to open a clicked _Favorites_ document in ane tab then you need to disable document the previewMode is the settings:
1. Use _Command Palette_ to open your settings file ("Preferences: Open User Settings")
2. Add the "workbench.editor.enablePreview" property, and set it's value to _false_. 

