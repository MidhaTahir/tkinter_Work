## Tkinter Basics and Some Tkinter Projects 
___
**Tkinter** is the standard **GUI library** for Python.
Python when combined with Tkinter provides a fast and easy way to create *GUI applications*.

---
###WIDGET CREATION
---
For most widgets , tkinter syntax is as follows:

`from tkinter import *`
---
```python
window = Tk()
widget = Tk.Widger(parent_window,text=...,command=...,width=...,height=...)

window.mainloop() '''mainloop() is an infinite loop used to run the application, wait for an event to occur and process the event till the window is not closed'''
```
---
####Tkinter Widgets:

1. Button
2. Canvas
3. Checkbutton
4. Entry
5. Frame
6. Label
7. Listbox
8. Menubutton
9. Menu
10. Message
11. Radiobutton
12. Scale
13. Scrollbar
14. Text
15. Toplevel
16. Spinbox
17. PanedWindow
18. LabelFrame
19. tkMessageBox

---
###Standard Attributes:

Let us look at how some of the common attributes, such as sizes, colors and fonts are specified.

* Dimensions
* Colors
* Fonts
* Anchors
* Relief styles
* Bitmaps
* Cursors

___
