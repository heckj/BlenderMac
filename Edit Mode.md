"tab" to toggle between Object and Edit mode within the 3D View point. To add new object, switch to object mode.

In edit mode - MANY more tools become available on left side.

Vertex selection - "1" (on keyboard)
Edge selection - "2" (on keyboard)
Side/Face selection - "3" (on keyboard)

left-click to select
shift-left-click to select an additional item

*FOCUS FOLLOW MOUSE* - you must have the mouse cursor within the bounds of the 3D Viewport for any keyboard commands to take effect.

shift-a - add mesh
g - grab
s - scale
r - rotate

With something selected, you can invoke a command entirely through keyboard:

\[command, constraint modifier, amount\]

> Note: moving something edit mode does *not* move the objects origin point. To reset the origin, **GO BACK TO OBJECT MODE**: left-click the mesh to select it, right-click (2-finger-tap) to activate a contextual menu, choose "Set Origin" > "origin to geometry" 

Transform commands take effect based on either a number, if provided, or based on mouse cursor movement. Hold down shift while moving the mouse cursor to make smaller adjustments.

## Extending Geometry

**Extrude** - "e" with face, edge, or vertex - pulls out and extends the mesh based on what you've selected. Most frequently you'll be extruding faces.
(enable 'face selection' with "3" on the keyboard)

**Loop-cut** - "ctrl-r" - cuts a ring (or loop) around the mesh. One activated, markers appear based on your cursor position to select the cut. left-click (or single tap on touchpad) to select the loop cut orientation. You can then slide it around with further mouse movement, until you click again (single tap) which looks the location into place.

You can also make multiple cuts at once by adding a number after you activate the loop-cut tool with ctrl-"r". For example, "ctrl-r", "4", move cursor to select orientation, click to select, move cursor to slide into position, click to set in place.

You can also left-click (two-finger-tap) to cancel or stop, or the "escape" key to back out a bit.

### Inset

With a face selected (or multiple faces):
- "i" to enable inset
- move mouse cursor to size the inset within the face

## Adjusting Geometry - Vertex controls

Enable proportional editing: "o"
- select a vertex (or several)
- "o" to enable proportional editing
- two-finger drag up or down changes the size of the effect mode (dragging up is bigger)
- "g" to grab the vertex and move it
Nearby vertices will be adjusted based on the size of the control area and how far you move the vertex.

### Edge slide

slides a vertex, or several, on existing geometry, useful for adjusting the overall form while sticking close to existing geometry. The vertex or vertices will slide between the surrounding vertices.

- select vertex or vertices
- "g", "g"
- move mouse cursor to push the vertex (or vertices) along edges of current geometry.

## Adjusting Geometry - Edge controls

### Selecting a Loop Cut

- choose "2" for edge mode
- select an edge
- hold option while selecting the next edge in the loop

### Shrink or Fatten

- with edge (loop) selected:
- option+"s"
- move the cursor to shrink or fatten that loop

### Edge slide

slides an edge along the existing geometry, useful for adjusting the overall form while sticking close to existing geometry. The edge will slide between the two sides opposite it.
- select edge (or loop)
- "g", "g"
- move mouse cursor to push the edge(s) along the current geometry.

### Sphereize

- with edge loop selected
- shift+option+"s"
- moving the mouse cursor increases the effect to attempt to conform the loop to match the surface of a sphere.

### Flatten

Flattens the edge loop against the "z" axis.
- with edge loop selected
- "s", "z", 0
You could replace "z" in that key sequence with either "x" or "y" to flatten against a different axis.