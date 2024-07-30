# Not maintained:
This fork is not currently maintained and may have bugs.
Feel free to fork, however pull request or bug reports will not be answered.

Currently 30/07/2024 project status is OK.

# What's this?
This is a clone of Probuilder 5.1.1 before they started f@ck!ng around with the probuilder window and associated menus.
It still works for my own project and I'm cloning it here so that my editor doesn't stop working.

# ⚠️ DISCLAIMER
We are not affiliated with Unity in any way. Old versions of Unity products are not supported nor recommended by Unity, and no support will be provided for using said products. Use at your own risk, and do not bother the folks at Unity if you decide to use this.

# What's new in version 5.0
https://docs.unity3d.com/Packages/com.unity.probuilder@5.1/manual/whats-new.html

Summary of changes in ProBuilder package version 5.0.

The main updates in this release include:

Added  
ProBuilder now supports a special modal "tool" mode for some features (the new Cut tool, and the refactored Shape and Poly Shape tools). Because of these changes, the other features that have a more immediate effect haven been rebranded "actions". For more information, see Tools vs. actions.  
Added a new Cut tool that allows you to add points on an existing face to define a new sub-face.  
Added a new Selection X-Ray option to highlight hidden element selections with a muted color. The default shortcut is Ctrl/Alt+Shift+X (modifiable in the Shortcuts Manager), and you can also access it through the ProBuilder menu (Tools > ProBuilder > Interaction > Toggle X Ray).  
Added a new preview selection for the Select Path action.  


Updated  
The new Shape tool has been completely rebuilt as an EditorTool.  
The Poly Shape tool is now an EditorTool.  


Fixed  
Fixed Undo so that it only reverts the last action, instead of all actions performed.  
Selection, picking and highlight shaders have been updated to be compatible with SRPs as well as with orthographic cameras (there are several bug fixes that directly support these adjustments).  
For a full list of changes and updates in this version, see the ProBuilder package changelog.  
