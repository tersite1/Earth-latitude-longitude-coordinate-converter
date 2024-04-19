
# Coordinate Converter

## Overview
The Coordinate Converter is a simple, user-friendly application built using Python's Tkinter library. It facilitates the conversion between geographic coordinates (latitude, longitude, and ellipsoidal height) and 3D Cartesian coordinates (X, Y, Z). This tool is ideal for geospatial professionals, students, and anyone interested in geographic information systems (GIS).

## Features
- Convert geographic coordinates to 3D Cartesian coordinates.
- Convert 3D Cartesian coordinates back to geographic coordinates.
- User-friendly graphical interface.
- Precision calculations based on the WGS84 ellipsoid model.

## Parameters
### Constants for WGS84
- `a = 6378137.0` — Semi-major axis
- `f = 1 / 298.257223563` — Flattening
- `e2 = f * (2 - f)` — Square of eccentricity

You can simply change these parameters if it needs to be adjusted to other datum. Verification of accuracy is written in "GPS Explantory.pdf", and shows fairly high accuracy.

## Installation

To run the Coordinate Converter, you need Python installed on your computer (Python 3.6+ recommended). Follow these steps to get started:

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/coordinate-converter.git
   ```
2. **Navigate to the cloned directory:**
   ```
   cd coordinate-converter
   ```

## Usage

To use the Coordinate Converter, execute the following command from the terminal:
```
python converter.py
```

Upon running the application, you will see a graphical interface with two buttons:
- **3D Cartesian Converter:** Converts geographic coordinates to Cartesian coordinates.
- **XYZ Converter:** Converts Cartesian coordinates to geographic coordinates.

Enter the required values in the dialog boxes that appear when you click on the respective buttons and the application will display the converted coordinates.

## Dependencies
This application relies on the following Python packages:
- `tkinter` — for the GUI components.
- `math` — for calculation of coordinate transformations.

Ensure these are installed in your Python environment. You can install any missing packages using `pip`:
```
pip install tk
```
(Note: Tkinter is usually included with Python, so you might not need to install it separately.)

## Contributing
Contributions to the Coordinate Converter are welcome! Please fork the repository, make your changes, and submit a pull request. You can also open issues for any bugs you encounter or enhancements you believe are worth adding.
