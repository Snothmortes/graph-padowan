`Project: GRAB` (Graph - Rewrite and Bugfix)
===========================================

`Presenting: 😍 **Graph 5.0** 😍`

Improvements
------------

`List:`

*   Multiselect items from list
*   Foldable list
*   Recolor font logo to fit set font color (like the rest.... duh...)
*   F2 to rename

`Labels:`

*   Border on labels
*   Group labels onto functions
*   Framework incorporation for seek and replace
*   Alignment (basically another CAD-layer with its own grid)
*   `LaTeX/Mathematics integration`
*   Enter should default to `OK`
*   DON'T redraw on moving labels... (it's idiotic and a waste of clock cycles)

`Shading:`

*   Area calc for shading
\- Tab index order in 'Insert Shading > 2nd function' should be rearranged from 1>2>3>4 to 1>3>2>4

`Other:`

*   Rewrite to `C#`
*   Customizable commands
*   MACROS
*   Custom compiler
*   Interface
*   IDE
*   Ribbons
*   More gathered settings
*   Standard color picker
*   Drawable line segments
*   Fix navigation:
    
    Space hold
    
    `Move`
    
    Middle button hold
    
    `Move`
    
    Space
    
    Right click
    
*   Customizable/selectable axies

Bug fixes
---------

`Ticket #001`

*   Dragging nested shading onto itself will cause it to dislodge from its parent:
*   Upon redrawing (Alt+TAB) of graph: `"Error: Access Violation"` occurs.
*   Upon saving and restarting file, the shadings have disappeared from the sheet.

`Ticket #002`

*   Label locations aren't absolute. They move when zooming.
*   Label sizes aren't scaled with zooming.

`Ticket #003`

*   When you make a modal dialog, it should be MODAL
*   ie: You shouldn't be able to zoom when the dialog is open
