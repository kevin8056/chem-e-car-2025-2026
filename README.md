# Chem-E-Car 2025–2026

Mechanical design files for our AIChE Chem-E-Car entry. Every part below has an
STL you can spin in your browser — **click any `.stl` link and GitHub renders it
in 3D**, no download, no CAD licence.

All dimensions in millimetres. Drawings drawn by Kevin, March 2026.

---

## Parts

### Encoder mount

<img src="images/encoder_mount.png" width="380" align="right">

Bracket carrying the wheel encoder against the drivetrain.

| | |
|---|---|
| **Envelope** | 54.0 × 17.7 × 30.0 mm |
| **Key features** | Ø9.35 shaft bore, 2× Ø2.80 fasteners, 4× R5.00 fillets |
| **3D model** | [`cad/stl/encoder_mount.stl`](cad/stl/encoder_mount.stl) |
| **Drawing** | [`docs/encoder_mount_drawing.pdf`](docs/encoder_mount_drawing.pdf) |
| **Source** | [`cad/source/encoder_mount.ipt`](cad/source/encoder_mount.ipt) |

<br clear="all">

### PCB standoff

<img src="images/pcb_standoff_v1.png" width="380" align="right">

Tray that lifts the control board off the chassis and holds it at the corners.

| | |
|---|---|
| **Envelope** | 91.1 × 66.1 × 6.0 mm |
| **Mounting pattern** | 85.00 × 60.00 mm, 4× Ø2.30 through / Ø6.10 boss |
| **Standoff height** | 3.00 mm |
| **3D model** | [`cad/stl/pcb_standoff_v1.stl`](cad/stl/pcb_standoff_v1.stl) |
| **Drawing** | [`docs/pcb_standoff_v1_drawing.pdf`](docs/pcb_standoff_v1_drawing.pdf) |
| **Source** | [`cad/source/pcb_standoff_v1.ipt`](cad/source/pcb_standoff_v1.ipt) |

<br clear="all">

### Speaker clamp

<img src="images/speaker_clamp_v3.png" width="380" align="right">

Split retaining ring clamping the speaker to its mounting face.

| | |
|---|---|
| **Envelope** | 46.8 × 37.4 × 1.8 mm |
| **Features** | Two-tab clamp, split ring |
| **3D model** | [`cad/stl/speaker_clamp_v3.stl`](cad/stl/speaker_clamp_v3.stl) |
| **Drawing** | *not yet drawn* |
| **Source** | [`cad/source/speaker_clamp_v3.ipt`](cad/source/speaker_clamp_v3.ipt) |

<br clear="all">

---

## Repository layout

| Path | Contents |
|---|---|
| [`cad/stl`](cad/stl) | Meshes — click any file for GitHub's 3D viewer |
| [`cad/step`](cad/step) | STEP exports for other CAD packages |
| [`cad/source`](cad/source) | Autodesk Inventor part files (`.ipt`) |
| [`docs`](docs) | Dimensioned drawings — render inline on GitHub |
| [`images`](images) | Renders used above |
| [`code`](code) | Microcontroller and analysis code |
| [`data`](data) | Test and calibration runs |

## Working with these files

- **Just looking?** Click any `.stl` above. Drag to spin, scroll to zoom.
- **Printing?** All parts modelled in mm; STLs export at that scale directly.
- **Editing?** Open the `.ipt` in Inventor 2024 or later, or import the STEP.

## Licence

*Add one — [CERN-OHL-S v2](https://cern-ohl.web.cern.ch/) is the usual pick for
open hardware; CC BY-SA 4.0 for the drawings and documentation.*
