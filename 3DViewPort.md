## Coordinate System

Right-handed chirality
Z - up/down (+ up) - BLUE
X -  forward/back - RED
Y - right/left - GREEN

(Note: this is 90° off what RealityKit and SceneKit use. Also right-handed, the positive Z axis points towards the camera/viewer, positive Y axis points up, and positive X axis points to the right).

Tools, game systems, and their coordinate systems:
https://miro.medium.com/v2/resize:fit:1400/format:webp/1*IWv0KVHPnf_xxL05Vh7oVQ.png

In Blender, the color "orange" represents selection

## Multitouch Gestures

2-finger-drag: Orbit
Ctrl + 2-finger-drag: Zoom
Cmd + 2-finger-drag: Zoom
Shift + 2-finger-drag: Pan
2-finger-tap: equivalent to right-click

The app window **must** be active for multi-touch gestures to work with modifiers. When it's not the focused window, 2-finger-drag only Orbits, regardless of modifiers selected and held.

You can also navigate by using the 3D gizmo in the upper-right-hand corner.

*FOCUS FOLLOW MOUSE* - you must have the mouse cursor within the bounds of the 3D Viewport for any keyboard commands to take effect.

## Orthographic and Perspective Views

Orthographic modes are "straight on" and don't reflect any perspective. If you rotate the view off that straight-on view, it enables perspective mode. When you're manipulating geometry in [[Edit Mode]], it can be extremely useful to be in one of the orthographic views, or you can constrain the editing effects using a modifier key.

You can tape on the ends of the 3D gizmo in the upper right corner of the 3D Viewport to select into one of those mode, or use a key combination to jump there. If you have a numeric keypad on your keyboard, the numeric keys on that pad will jump to the same views as the menu selection.

Use the "~" key to bring up a circular menu that lets you change the current view:
"~","8" - top view
"~","7" - front view
"~","9" - back view
"~","4" - left view
"~","6" - right view
"~","2" - bottom view

"~","3" - view selected
"~","1" - view camera


## View Rendering

- Wireframe
- Solid
- Shading
- Rendering

"z" brings up a radial menu that lets you choose between the various rendering modes. Jumping to "wireframe" mode can be useful in [[Edit Mode]] to select vertices and/or faces that are otherwise hidden.

## Keyboard View Controls

"t": toggle show/hide of left-hand side tools
 - use Shift + Spacebar to activate a quick selection.
"n": toggle right-hand sidebar
 - item, tool, view, and create inspectors/tool choice

option-"z" - toggle x-ray mode

## ViewPort Overlay

You can enable "statistics" in the viewport overlays (pull down menu from the top of the panel, right-hand side), which enabled # objects, vertices, edges, faces, and triangles in the current scene.

## 3D ViewPort Modes

- Object Mode
The default mode for the 3D viewport. Objects can also be found in the outliner, and may (or not) have geometry in the viewport.
Any mesh is an object - and has an "origin point", represented by a bright orange dot when the object is selected. 

Moving an object in object mode (using the "g" to grab it, for example) moves the origin with the object.

- For mesh:
	- [[Object Mode]]
	- [[Edit Mode]]
	- Sculpt Mode
	- Vertex Paint
	- Weight Paint
	- Texture Paint
- For Armature
	- Edit Mode
	- Pose Mode
