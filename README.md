# The Visual Debugger Tool

This repository contains the sources of paper submitted to the [International Conference on Software Maintenance and Evolution (ICSME) 2022](https://cyprusconferences.org/icsme2022/) and associated artifacts.
The paper described the [open-source](https://github.com/timKraeuter/VisualDebugger) [Visual Debugger](https://plugins.jetbrains.com/plugin/16851-visual-debugger) Tool.

# Demonstration of the Visual Debugger
Follow the [screencast](https://www.youtube.com/) doing the following steps:
1. Clone the Visual Debugger [repository](https://github.com/timKraeuter/VisualDebugger) using git.
2. Open the repository clone using IntelliJ IDEA as a new project.
3. Install the Visual Debugger plugin from the IntelliJ IDEA marketplace (```File < Settings < Plugins``` and search for **Visual Debugger**).
4. Go to the class ```PartsListTest``` and set a breakpoint at line 14 (directory: ```src/test/java```, package: ```no.hvl.tk.visual.debugger.manueltests.partsList```).
5. Start debugging and activate the Visual Debugger in the Visual Debugger tool window.
6. Open the Visual Debugger tool by clicking on the "Launch user interface" button in the Visual Debugger tool window.
7. Enjoy the Visual Debugger tool.

# Further resources
- More information about the tool including screenshots can be found at the [tool plugin page](https://plugins.jetbrains.com/plugin/16851-visual-debugger) in the IntelliJ IDEA marketplace.
- The visualization component of the Visual Debugger can be found [here](https://github.com/timKraeuter/object-diagram-modeler).
- You can edit object diagrams created during debugging using my [object diagram modeler](https://timkraeuter.com/object-diagram-modeler/).