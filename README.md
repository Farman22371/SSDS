**Smart Structural Design System (SSDS)**

Desktop application that automates RC building modeling, analysis and design through the ETABS v21 COM API.

**Download:** [SSDS_Setup_v1.0.0.exe](https://github.com/Farman22371/SSDS/releases/latest)

Final-Year Project, BSc Civil Engineering, University of Engineering and Technology (UET) Mardan, 2025-2026

---

About

SSDS (Smart Structural Design System) is a Python/PyQt5 application that connects to ETABS v21 through its COM API to build structural models, run analysis and perform design for reinforced concrete (RC) buildings. It replaces a long manual modeling workflow with an automated one.

Reported result: modeling time reduced from about 8 hours (manual) to about 8 minutes (automated).

**Features**

- Graphical interface built with Python and PyQt5
- Automatic ETABS v21 model creation, analysis and design through the COM API (comtypes)
- RC building configurations with beams, columns, slabs, shear walls and stairs
- Seismic input data for 93 districts of Pakistan
- Design and loading standards: ACI 318-19, ASCE 7-22 and Building Code of Pakistan (BCP) 2021
- Windows installer built with PyInstaller and Inno Setup

**Requirements**

- Windows
- ETABS v21 (licensed copy, not included with SSDS)

**Installation**

1. Go to the [Releases page](https://github.com/Farman22371/SSDS/releases) and download SSDS_Setup_v1.0.0.exe from Assets.
2. Run the installer and follow the steps.
3. Open ETABS v21.
4. Launch SSDS and enter your building data.

Note: Windows may show a SmartScreen warning because the installer is not code-signed. Click "More info", then "Run anyway".

**Validation**

[Describe how you checked the results, for example: results compared with manually built ETABS models for n test buildings, with x% difference.]

**Tools and technologies**

Python | PyQt5 | ETABS v21 | ETABS COM API | comtypes | PyInstaller | Inno Setup

**Author**

Farman Ullah
BSc Civil Engineering, UET Mardan
Final-Year Project supervised by Engr. Sami Ullah, Lecturer, UET Mardan

**Contact**

- Email: engrfarmanullah4@gmail.com
- LinkedIn: [add your LinkedIn URL]
- GitHub: [github.com/Farman22371](https://github.com/Farman22371)

**Disclaimer**

SSDS is an academic project. Results should be checked by a qualified engineer before use in real design work. ETABS is a product of Computers and Structures, Inc. and is not affiliated with this project.
