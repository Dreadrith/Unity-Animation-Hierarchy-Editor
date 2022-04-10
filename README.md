Unity Animation Hierarchy Editor
================================
Originally created by s-m-k
https://github.com/s-m-k/Unity-Animation-Hierarchy-Editor

This Fork is made by Dreadrith#3238

Original description:
This utility will help you refactor your Unity animations.

Place the AnimationHierarchyEditor.cs file in YourProject/Editors/ folder to make it work. Then you'll be able to open Animation Hierarchy Editor window by clicking on Window > Animation Hierarchy Editor.

The editor will work if you select an animation clip.

Fork Improvements:
- Distinct paths will cumulate and display all together
- Replacing a path with a path that already exists will now change properties that will be unique and ignore properties that would overlap.
- Added Regex option for replacing paths
- Added a reset button for replacing Paths
- Cleaned up and simplified code
- Polished UI