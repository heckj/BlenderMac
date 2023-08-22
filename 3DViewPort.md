## Coordinate System

Right-handed chirality

- X: forward/back - 🔴
- Y: right/left - 🟢
- Z: up/down (+ up) - 🔵

(Note: this is 90° off what RealityKit and SceneKit use. Also right-handed, the positive Z axis points towards the camera/viewer, positive Y axis points up, and positive X axis points to the right).

Tools, game systems, and their coordinate systems:
![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*IWv0KVHPnf_xxL05Vh7oVQ.png)

In Blender, the color "orange" represents selection

## Multitouch Gestures

- 2-finger-drag: Orbit
- Ctrl + 2-finger-drag: Zoom
- Cmd + 2-finger-drag: Zoom
- Shift + 2-finger-drag: Pan
- 2-finger-tap: equivalent to right-click

The app window **must** be active for multi-touch gestures to work with modifiers. When it's not the focused window, 2-finger-drag only Orbits, regardless of modifiers selected and held.

You can also navigate by using the 3D gizmo in the upper-right-hand corner.

*FOCUS FOLLOW MOUSE* - you must have the mouse cursor within the bounds of the 3D Viewport for any keyboard commands to take effect.

## Orthographic and Perspective Views

An orthographic view is aligned with one of the axis, showing a "straight on" view without perspective. When you rotate away, the 3D Viewpoint distorts the image slightly to show perspective. 

Editing within orthographic mode is naturally aligned to axis. Achieve the same effect when in [[Edit Mode]] with perspective camera by using a constraint modifier keyboard shortcut .

### Gizmo
Tap on the round points at the ends of the lines in the 3D gizmo to jump into an orthographic view. Tap again to jump to the opposite view on that axis.
Red (x-axis) for front/back view, green (y-axis) for right and left side view, and blue (z-axis) for top/bottom view.

### Keyboard shortcuts
Use the "~" key to bring up a circular menu that lets you change the current view:

- "~","8" - top view
- "~","7" - front view
- "~","9" - back view
- "~","4" - left view
- "~","6" - right view
- "~","2" - bottom view
- "~","3" - view selected
- "~","1" - view camera

If you have a numeric keypad on your keyboard, the numeric keys on that pad will jump to the same views as the menu selection.

## View Rendering

"z" brings up a radial menu that lets you choose between the various rendering modes:
- 4 - Wireframe
- 6 - Solid
- 2 - Shading
- 8 - Rendered

Jumping to "wireframe" mode can be useful in [[Edit Mode]] to select vertices and/or faces that are otherwise hidden.

## Keyboard View Controls

- "t": toggle show/hide of left-hand side tools
  - use Shift + Spacebar to activate a quick selection.
- "n": toggle right-hand sidebar
  - item, tool, view, and create inspectors/tool choice
- option-"z" - toggle x-ray mode

## ViewPort Overlay

You can enable "statistics" in the viewport overlays (pull down menu from the top of the panel, right-hand side), which enabled # objects, vertices, edges, faces, and triangles in the current scene.

## 3D ViewPort Modes

### Object Mode

The default mode for the 3D viewport. Objects can also be found in the outliner, and may (or not) have geometry in the viewport.
Any mesh is an object - and has an "origin point", represented by a bright orange dot when the object is selected.

Moving an object in object mode (using the "g" to grab it, for example) moves the origin with the object.

### For mesh:

- [[Object Mode]]
- [[Edit Mode]]
- Sculpt Mode
- Vertex Paint
- Weight Paint
- Texture Paint

### For Armature

- Edit Mode
- Pose Mode
