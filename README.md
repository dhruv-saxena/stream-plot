stream-plot
===========

A data visualization tool for streaming data. It is based on Galry, an open-source tool by Cyrille Rossant.


Features
---------

- Auto-focus. As streaming data gets displayed, the plot pans and zooms appropriately and fits the data to the screen.
- Key press triggers the program to save the last n samples acquired

Dependencies
-----------

- Python 2.7 - http://www.python.org/
- Open GL >= 2.1 - Your graphics drivers should support OpenGL 2.1
- PyOpenGL >= 3.0.2 - http://pyopengl.sourceforge.net/
- PyQt4 with openGL bindings - http://www.riverbankcomputing.com/software/pyqt/download
- NumPy - http://www.numpy.org/
- matplotlib - http://matplotlib.org/


This project uses Galry 0.1.0.rc1 ( http://rossant.github.io/galry/ ) which is bundled in the form of source code.


How to use
----------

- Install all dependencies.
- See src/streamplot_test*.py for examples. Run "python streamplot_test2.py" in the command line.

Shortcuts
---------

When the plot figure is in focus, the following shortcuts may be used.

- 'a' - Toggle auto-focus
- 'd' - Save the last n samples into a csv file
- 'f' - Save all buffered samples into a csv
- 'z' - Zoom-in along the time axis
- 'x' - Zomm-out along the time axis
- 'c' - Save samples visible on screen to a csv

The entire list of available shortcuts may be seen by pressing 'h' when the window is in focus.
