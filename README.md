# FSOC Visual Camera Tracking

The complete project is in **FSOC-visual-camera-tracking.zip**. Download and extract the ZIP to preserve all source folders, then run the commands below from the extracted folder.

## Start the local web interface

Requires Python 3.11 or newer. No extra packages are required for the web interface.

```sh
python -m gui.web
```

Open http://127.0.0.1:8000 in your browser.

## Run tests

```sh
python -m unittest discover -v
```

All 66 tests passed before upload on September 5, 2026.

## Included

Simulation, virtual camera, beacon detection, classical and AI-assisted tracking, pan/tilt control, benchmarks, model asset, documentation, sample results, local web interface, and the original Tkinter desktop app.

This is a deterministic software simulation for coarse alignment of mobile FSOC terminals. Physical camera, servo hardware, and optical-link performance are not validated in this release.

The ZIP contains the original project README with full details.
