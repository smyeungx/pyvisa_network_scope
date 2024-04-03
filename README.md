# pyvisa_network_scope
Rigol DHO800 DHO900 Series Network DSO Data Acquisition

An example Python script to setup the Rigol DHO800/900 Series Network Oscilloscope for various kind of measurement automation.  For instance, the Python script is tested on VS Code with Python 3.11 on Windows 10 for Magnetic Resonance Imaging spectrometer loopback timing diagnostic for RF and Gradient signal.  Tested on DHO824 and DHO924.  

References  
DHO900 Series Introduction: https://www.rigolna.com/products/rigol-digital-oscilloscopes/dho900/  
DHO900 Series LXI/SCPI Programming Guide: https://beyondmeasure.rigoltech.com/acton/attachment/1579/f-f798be30-18ec-4846-9ffe-40b125f49133/0/-/-/-/-/DHO800900_ProgrammingGuide_EN.pdf
Nicely Designed Text User Interface (TUI) package, with Scope as a class:  https://pypi.org/project/rigol-ds1000z/  
Intuitive USB Example: https://gist.github.com/pklaus/7e4cbac1009b668eafab  
Another Example: https://github.com/AlexZettler/Rigol1000z  
