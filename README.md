# XRDStudio v1.1

**A simple desktop application for X-ray diffraction (XRD) analysis.**

XRDStudio is a Python-based desktop application designed to help researchers visualize, process, and analyze X-ray diffraction patterns through an accessible graphical interface. It brings essential XRD analysis tools into one workspace, making routine data processing more convenient without requiring users to write code.

## ✨ Features

- **XRD pattern visualization** — Import, display, and inspect diffraction patterns.
- **Data processing** — Apply smoothing and background estimation to improve pattern visualization.
- **Peak detection** — Identify diffraction peaks for further analysis.
- **Phase identification** — Compare observed peak positions against a reference peak database.
- **Peak-profile fitting** — Perform exploratory pseudo-Voigt peak fitting.
- **Data export** — Export processed diffraction data for further analysis.
- **Research-oriented interface** — Work with experimental data through a desktop GUI.

## 🚀 Installation

Getting started is straightforward. You do not need to manually combine installer files.

### Option 1: Download the Windows installer

1. Open the [XRDStudio Releases](https://github.com/research-pedputra/XRDStudio/releases) page.
2. Download the Windows installer for **v1.1**, if available.
3. Double-click the downloaded `.exe` file.
4. Follow the installation wizard and launch XRDStudio from the Start menu or desktop shortcut, if provided.

### Option 2: Run from source

If a Windows installer is not available, install Python 3.10 or later, download or clone this repository, and run:

```bash
python -m venv .venv
```

Activate the environment:

**Windows — Command Prompt**
```bat
.venv\Scripts\activate
```

Install XRDStudio:

```bash
python -m pip install --upgrade pip
python -m pip install -e .
```

Launch the application:

```bash
xrdstudio
```

## 📊 Supported data

XRDStudio supports common two-column diffraction data files, including `.xy`, `.xye`, `.txt`, `.csv`, and `.dat`. The expected input contains the diffraction angle (\(2\theta\)) in the first column and intensity in the second.

## 🔬 Development status

**Version 1.1** provides core XRD data visualization and processing features. Advanced crystallographic analysis is a continuing development goal.

Full crystallography-constrained Rietveld refinement, quantitative phase analysis, and comprehensive CIF-based structural refinement should not be considered available unless explicitly implemented and validated in a future release.

## 📄 License

See the repository's `LICENSE` file for licensing and redistribution terms.

---

*Developed for researchers working with experimental X-ray diffraction data.*
