# KiCad Project Template Library

This repository contains a standardized project structure template for KiCad, designed to support collaborative development, enforce documentation consistency, and improve long-term maintainability.  
It is compatible with both **macOS** and **Windows** platforms, and is ready for use with **KiCad 9.0 or later**.

---

### 📁 Directory Structure

```plaintext
── Lib/                         # Component library directory
│   ├── lib_sym/                # Schematic symbol libraries (.lib / .kicad_sym)
│   ├── lib_fp/                 # Footprint libraries (.pretty)
│   └── lib_3d/                 # 3D model files (.step / .wrl)
├── Manufacturing/              # Fabrication and assembly deliverables
│   ├── Assembly/               # Pick-and-place files, BOMs, assembly drawings
│   └── Fabrication/            # Gerber files, drill files, stackups, fab notes
├── Notes/                      # Design notes and graphical resources
│   ├── Datasheet/              # Component datasheets and technical references
│   └── Images/                 # Board renders, mechanical drawings, photos
├── README.md                   # Project overview and usage instructions
├── <project_name>.PDF          # Exported schematic in PDF format
├── <project_name>.kicad_pro    # KiCad project file
├── <project_name>.kicad_sch    # Top-level schematic file
└── <project_name>.kicad_pcb    # PCB layout file
```
