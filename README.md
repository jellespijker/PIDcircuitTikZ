# Latex Tikz Library with useful symbols

## circuit Process and Instrumentation Diagram (ISO14617)

An extension for the Tikz circuit library. Which allows the drawing of P&IDs.
Symbols are added when needed. If a symbol is missing and you need it. Add it yourself and **SHARE**! or create an issue for a feature request, and pray that I have time to implement it.

![example](example.jpg?raw=true)

Implementation of the following norms:
* 14617-1 General information and indexes
* 14617-2 Symbols having general application
* 14617-3 Connections and related devices
* 14617-4 Actuators and related devices
* 14617-5 Measurement and control devices
* 14617-6 Measurement and control functions
* 14617-7 Basic mechanical components
* 14617-8 Valves and dampers
* 14617-9 Pumps, compressors and fans
* 14617-10 Fluid power converters
* 14617-11 Devices for heat transfer and heat engines
* 14617-12 Devices for separating, purification and mixing
* 14617-13 Devices for material processing
* 14617-14 Devices for transport and handling of material
* 14617-15 Installation diagrams and network maps

## Installation

1. Clone the project  

    _Single project_:

2. Place the files `pid\tikzlibrarycircuits.pid.code.tex`, `pid\tikzlibrarycircuits.pid.iso14617.code.tex`, `pid\pgflibraryshapes.gates.pid.code.tex` and `pid\pgflibraryshapes.gates.pid.iso14617.code.tex` in the same folder as your main `tex` file.

    _System-wide installation_:  
2. Copy files `pid\tikzlibrarycircuits.pid.code.tex`, `pid\tikzlibrarycircuits.pid.iso14617.code.tex`, `pid\pgflibraryshapes.gates.pid.code.tex`, `pid\pgflibraryshapes.gates.pid.iso14617.code.tex` and `draftdrawing.cl` in to `<TEXMFHOME>\tex\latex\PIDcircuitTikz\`  
or clone complete project in `<TEXMFHOME>\tex\latex\`

**FEEL FREE TO CONTRIBUTE!**
All ISO 14617 symbols can be found online at [iso.org](https://www.iso.org/obp/ui#search), just search for 14617 and go to the graphical symbols tab.
