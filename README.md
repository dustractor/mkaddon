mkaddon
---

#####This script is for generating the boilerplate of an addon.

Installation is per normal method for blender via Blender's User Preferences --> "Install from file…".

The interface to the addon consists of a panel in the sidebar of the Text-Editor.  Initially this panel displays an empty list, which is for displaying and/or selecting an addon, and a button which is for creating an addon.

######Start by clicking the button labeled "mkaddon".

A text-block is created and displays in the editor window.

Various sections of the addon are initially disabled.  Toggle buttons for each section are on a row next to each addon on the list.

Sections are enabled or disabled using toggle buttons along the row of the list-display for each addon.  Visibility for each section is toggled at the header for each section.

*  GPL Licence
*  Blender Addon Information (bl_info)
*  Python Modules ( import modules such as bpy )
*  Operator
*  Panel
*  Registration


######At the very bottom there is a box for saving to a specific location.  Note that this is different from using the built-in functionality provided by the text editor.

I have tested that this addon downloads ok, installs ok, and enables ok.  I have also tested that it's product runs, but so far this is only week one for this project and I'm putting it on a back burner for now.