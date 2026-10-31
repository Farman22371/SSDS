Smart Structural Design System
==============================
Version 1.0.0  |  Professional RC Building Automation

REQUIREMENTS
------------
- Windows 10 or 11 (64-bit)
- ETABS v19, v20, or v21 must be installed and licensed
  (the application connects to ETABS via its COM API)
- Minimum 4 GB RAM recommended
- Screen resolution: 1280x720 or higher

INSTALLATION
------------
1. Run SSDS_Setup_v1.0.0.exe
2. Follow the installation wizard
3. Optionally create a desktop shortcut
4. Launch from Start Menu: Smart Structural Design System

FIRST RUN
---------
- On first launch, comtypes will generate ETABS type libraries
  (this takes ~10-30 seconds on first run, faster after that)
- Make sure ETABS is NOT already open when clicking "Generate Model"

USAGE WORKFLOW
--------------
1. Fill in Project Info (name, code, units)
2. Set Geometry (stories, bays, sections)
3. Configure Seismic parameters (select district)
4. Set Loads (SDL, Live, Wall loads)
5. Click "Generate ETABS Model"
6. Click "Run Analysis"
7. Click "Run Design"
8. Go to Reports tab → Generate PDF

TROUBLESHOOTING
---------------
- "ETABS not found": Ensure ETABS is installed and registered
- "comtypes error": Run the app once with ETABS installed; it will
   auto-generate required type libraries in AppData\SSDS\comtypes_gen
- Crash on startup: Check crash_log.txt in the install folder
- Antivirus warning: Add the install folder to your AV whitelist
  (false positive due to PyInstaller packaging)

CONTACT
-------
For support, refer to the project documentation or contact the developer.
