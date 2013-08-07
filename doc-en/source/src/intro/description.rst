About Cecilia
================

Cecilia is an audio signal processing environment. Cecilia lets you create your own GUI (grapher, sliders, toggles, popup menus) using a simple syntax. Cecilia comes with many original built-in modules for sound effects and synthesis.

Previously written in tcl/tk, Cecilia (version 4, deprecated) used the Python-Csound API for communicating between the interface and the audio engine. Version 4.2 is the final release of version 4.

Cecilia5 has been now entirely rewritten in Python/wxPython and uses Pyo, an audio engine written in C and created for the Python programming language. Pyo allows a much more powerful integration of the audio engine to the graphical interface. Since it is a standard python module, there is no need to use an API to communicate with the interface.