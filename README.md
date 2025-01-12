# Paint App

## Overview
The **Simple Paint App** is a lightweight drawing application created using PyQt6. Users can draw on a canvas with different tools such as a pencil, marker, eraser, and color selector. This project demonstrates PyQt6 capabilities, including event handling, GUI design, and drawing functionality.

## Features
- **Canvas:** A blank canvas where users can draw using different tools.
- **Tools:**
  - Pencil: Draw fine lines.
  - Marker: Draw thicker lines.
  - Eraser: Erase parts of the drawing.
  - Color Selector: Choose custom colors for drawing.
- **File Operations:**
  - New: Clear the canvas.
  - Save: Save the drawing as a PNG file.
- **Mouse Tracking:** Tracks and displays mouse coordinates on the status bar.

## Technologies Used
- **Python:** Programming language.
- **PyQt6:** GUI framework.

## How to Run
1. Ensure Python is installed on your system.
2. Install the PyQt6 library using pip:
   ```bash
   pip install PyQt6
   ```
3. Save the project files with the following structure:
   ```
   /PaintApp
   |-- main.py       # Main application file
   |-- /icons        # Folder containing icon files
       |-- pencil.png
       |-- brush.png
       |-- eraser.png
       |-- colors.png
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## Key Functionalities
- **Mouse Events:** The app responds to mouse presses, movements, and releases to enable drawing.
- **Dynamic Toolbar:** Use the toolbar to select tools and change drawing modes.
- **Save Feature:** Save your drawing to a file in PNG format.
- **Customizable Colors:** Choose your preferred drawing color using a color picker dialog.

## Future Enhancements
- Add undo/redo functionality.
- Support additional file formats (e.g., JPEG, BMP).
- Add shapes (e.g., rectangles, circles).
- Include a text tool.
- Make the app compatible with touchscreens.

## Acknowledgements
This project is a simple demonstration of PyQt6's drawing and GUI capabilities, inspired by beginner PyQt tutorials.
