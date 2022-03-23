# The Visual Debugger Tool

This repository contains the sources of [the paper](./paper.pdf) submitted to the [International Conference on Software Maintenance and Evolution (ICSME) 2022](https://cyprusconferences.org/icsme2022/) and associated artifacts.
The paper describes the [open-source](https://github.com/timKraeuter/VisualDebugger) [Visual Debugger](https://plugins.jetbrains.com/plugin/16851-visual-debugger) Tool.

# Demonstration of the Visual Debugger
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/lU_OgotweRk/0.jpg)](https://www.youtube.com/watch?v=lU_OgotweRk)

Follow the [demonstration](https://www.youtube.com/watch?v=lU_OgotweRk) doing the following steps:
1. Clone the Visual Debugger [repository](https://github.com/timKraeuter/VisualDebugger) using git.
2. Open the repository clone using IntelliJ IDEA as a new project.
3. Install the Visual Debugger plugin from the IntelliJ IDEA marketplace (```File < Settings < Plugins``` and search for **Visual Debugger**).
4. Go to the class ```PartsListTest``` and set a breakpoint at line 14 (directory: ```src/test/java```, package: ```no.hvl.tk.visual.debugger.manueltests.partsList```).
5. Start debugging and activate the Visual Debugger in the Visual Debugger tool window.
6. Open the Visual Debugger tool by clicking on the "Launch user interface" button in the Visual Debugger tool window.
7. Enjoy the Visual Debugger tool.

# Visual Debugger API
The Visual Debugging API is described [here](https://github.com/timKraeuter/VisualDebugger/tree/master/documentation#visual-debugging-api).

# Further resources
- More information about the tool including screenshots can be found at the [tool plugin page](https://plugins.jetbrains.com/plugin/16851-visual-debugger) in the IntelliJ IDEA marketplace.
- The **visualization component** of the Visual Debugger can be found [here](https://github.com/timKraeuter/object-diagram-modeler).
- You can edit object diagrams created during debugging using my [object diagram modeler](https://timkraeuter.com/object-diagram-modeler/).
- A short documentation of the visual debugger tool implementation can be found [here](https://github.com/timKraeuter/VisualDebugger/blob/master/documentation/README.md).
- There is also a description of the tool on [my website](https://timkraeuter.com//visual-debugger/).
