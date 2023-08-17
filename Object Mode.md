Interacting with objects, or meshes, within the scene.
Use "tab" to jump between [[Object Mode]] and Edit Mode ([[Edit Mode]]).

Click to select an object (single-finger tap)

## Common Controls

Select - left-click
Grab "g"
Rotate "r"
Scale "s"

You can sequence these with the \[command, constraint modifier, amount\] key pattern.

Constraint Modifiers:
"x" - constrain to the X axis
"y" - constrain to the Y axis
"z" - constrain to the Z axis
shift+"x" - constrain to both the Y and Z axis 
shift+"y" - constrain to both the X and Z axis 
shift+"z" - constrain to both the X and Y axis 

The first time you trigger an axis constraint, it's constraining against global coordinates. If you hit the same constraint modifier again, it toggles to constraining against the local coordinate system for the object.

Amount:
digits (1,2,3...) from the keyboard to count the units.

For example, selecting a cube (left click on it) and then pressing the following key sequence:
"s", shift+"z", 20
scales the cube by 20 along the X and Y axis.

> Note: When you're moving, scaling, or rotating in perspective mode, the operation happens based on your viewing angle in the 3D viewport. Best to go into orthographic modes (top, front, left, etc) if you want to keep things controlled along axis while moving, without having to specify constraining modifiers in the key sequence.

Delete : "x" - delete selected element

Add New Object : shift+"a"
