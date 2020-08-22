# Houdini_Agent_Footplant_Setup
A simple shortcut tool that helps configure Houdini's agent prep chopnet to use distance threshold for footplanting

## Instalation:

After downloading, copy the .shelf files to this folder on your machine:

Windows: C:\Program Files\Side Effects Software\Houdini xx.x.xxx\houdini\toolbar

Mac: Libary/Frameworks/Houdini Framework/Versions/xx.x.xxx/Resources/hodini/toolbar (Note that I am unfamiliar with Mac and don't know if this path is correct)

Linux: /opt/hfs xx.x.xxx/houdini/toolbar

After restarting houdini the "MB_Shelf" should be avalible to add to your shelf tray by clicking the "+" button next to your shelves titles, hovering over the "Shelves" option and scrolling down to "MB_Shelf".

This is simply an empty shelf I have included where the tools can be placed. Feel free to make your own shelf or place my tools in one of the existing shelfs.

After selecting a shelf to place the tools in, right click on the shelf tab or on an empty part of the shelf and select "Edit shelf tab".
In the new window select the "Tools" tab and scroll down the list. All my tools are prefixed with "MB" so they should show up there.
Simply select the tool you want in the shelf and click "Apply" and then "Accept" and the tool should be ready for use.

## Usage:

Select the CHOP net created by the agent prep node and click this tool. This will update all the bone nodes inside to use distance threshold as well as create a new parameter on the CHOP net for distance threshold.
NOTE: That this parameter might require you to go into the CHOP net and out again to be visible due to some limitations with the Houdini-Python interface.