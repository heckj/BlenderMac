
Simple Tree
shift+"a" -> select mesh (cylinder)
- panel in lower left allows you to control the number of vertices in the basic geometry.

edit mode
- select bottom face, scale up bottom
- select top face, scale down
- select side face, ctrl-r (loop cut), "3", click, click to add three loop cuts
- lock into orthographic mode (using gizmo - front or side view)
-  "e" to extrude, right-click (two-finger-tap) to lock in place.
- "s" to scale the extrusion, and move the mouse cursor to free scale "down and out" to make it sort of overlap.
- Repeat on each of the segments of the tree, selected by collection of faces.
- select bottom face
- "i" to inset the selected face, mouse cursor to move to select size.

Low-poly animal (bear)

- start with cube
	- tab to edit mode
	- loop cut vertically
	- select left side vertices, 'x' to delete
	- modifiers - wrench symbol in the inspector view
		- enable mirror modifier
			- enable clipping
- focus on blocking out the large components
The general pattern is adding loop cuts, grabbing faces and moving them in edit mode as needed to get rough shapes. Then, with certain faces selected, 'e' to extrude (make sure you're in orthographic mode, so they're not extruding in an odd direction). Extrude for each major section of the body - for example, upper arm, lower arm. You'll likely go back and add loop cuts to form the extremities further later.