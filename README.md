# MuMax3-How-To

[![License](https://img.shields.io/badge/GNU-General_Public_License_v3.0-green)](https://choosealicense.com/licenses/gpl-3.0/)

Installation, scripting, & data generation demo of computational micro and nanomagnetism in MuMax3. Formed & written by Onri Jay Benally, an Indigenous American quantum hardware engineer.
______________________________________________________________________________________________________________________________________________________
![image](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/4decf8c2-2a28-45b6-8d8d-220401dbfc4f)

Uses code heavily-modified for clarity, inspired from: (https://github.com/mumax/3) & (https://mumax.github.io/examples.html)

(Examples computed in this repository were performed on an NVIDIA (RTX4070 Ti Super) GPU, connected externally to a Microsoft Surface Pro 8).

||
|-----------|
| [How to Install and Run MuMax3 by Onri](https://github.com/OJB-Quantum/MuMax3-How-To/blob/main/Installing%20and%20Running%20MuMax3%20by%20Onri%20Jay%20Benally.pdf) |
| [Video Example of Onri's MuMax3 Hysteresis Plots in Python](https://youtu.be/YCUwEaX9SrI?si=I_m6b0n1USWKunFJ) |
| [Example MuMax3 Script in TXT Format](https://github.com/OJB-Quantum/MuMax3-How-To/blob/main/MuMax3_Hysteresis_Loop_Example.txt) |
| [Google Colab/ Jupyter Notebook Example of Data Imported From MuMax3 - Hysteresis Loop by Onri](https://github.com/OJB-Quantum/MuMax3-How-To/blob/main/Python%20Code_MuMax3%20Data%20Plots/Hysteresis_Loop_Example_2_by_MuMax_Locally_Run.ipynb) |
| [Video Animation of Magnetic Orders](https://youtu.be/X4hEEzAGyhM?si=5Lpkqnvpjs6UKjUY) |
| [Explanation of Hysteresis Curves & Coercivity](https://youtu.be/rGgKK3-wep4?si=bQ1aQ5gz3IZlJ2Qt) |
| [Micromagnetism Overview](http://micromagnetics.org/micromagnetism/) |
______________________________________________________________________________________________________________________________________________________
## If MuMax3 is installed already, start the GUI by typing the following 2 lines into a non-admin command prompt or non-admin PowerShell:
```bash
cd <directory_to_your_MuMax3_file>
```
```bash
mumax3 -i <your_MuMax3_TXT_file_name>
```

Note: MuMax3 scripts can be written as TXT file types. The above script will load and automatically run the script into a browser.

Online OVF file type visualization: (https://mumax.ugent.be/mumax-view). While using the viewer, you can load multiple OVF files to play an animation of the magnetization frame capture.
________________________________________________________________________________________________________________________________________________________
### Below is an example of a Hysteresis loop plotted in Python, provided in one of the examples above:
![Hysteresis Plot_Python_Blue](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/9df5d4aa-7bf2-439f-a7d6-d9862b5a283f)

### Magnetic material visualization example:
![Vector field after 2 minutes](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/30d1d710-f5a2-48e2-9b01-9162b3aedf91) ![Vector field after a couple more minutes](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/5eb4bf8a-cb1b-48c6-a422-6b3b72010f8f)

### Magnetic geometry (300 nm x 100 nm x 3 nm) visualization in 3D using [MuMax View](https://mumax.ugent.be/mumax-view) in the browser:
![ezgif-2-ce10ab426e](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/40d7ff7a-e8bb-4438-9cd8-eeff2aa36a89)

### More examples:
![Screenshot 2024-03-13 124721](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/4f6f514b-a03d-4e99-861a-53e36d6196f9)
![Screenshot 2024-03-13 125101](https://github.com/OJB-Quantum/MuMax3-How-To/assets/88035770/a583f8b5-8fa5-4ee7-8e5c-7163c567cb28)

