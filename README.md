---

# Shape Drawing Application

This Python application allows users to draw rectangles and squares on a canvas. Users can input the dimensions, position, and color of the shapes. The canvas can be exported as an image for visualizing the drawn shapes.

## Prerequisites

Before running the application, make sure you have the required dependencies installed. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the application by executing the `main.py` script:

   ```bash
   python main.py
   ```

2. Enter the canvas width and height.

3. Choose the canvas color by specifying either "white" or "black".

4. Start drawing shapes:
   - To draw a rectangle, enter "rectangle" and provide its position, width, height, and RGB color components.
   - To draw a square, enter "square" and provide its position, side length, and RGB color components.

5. To finish drawing, enter "quit".

6. The drawn canvas will be saved as `canvas.png`.

## Files

- `main.py`: The main script where users interact with the application. It takes user inputs for canvas dimensions, color, and shape details.
- `canvas.py`: Contains the `Canvas` class, responsible for creating the canvas and converting it to an image.
- `shapes.py`: Contains the `Rectangle` and `Square` classes, which define the properties and drawing methods for rectangles and squares.
- `design.txt`: Additional design-related information.
- `requirements.txt`: Lists the required dependencies for the project.
- `canvas.png`: Sample output image of the drawn canvas.

## How It Works

The application uses numpy and Pillow (PIL) libraries to create a canvas, draw shapes on it, and save the canvas as an image. The user's inputs are processed to create instances of the `Rectangle` and `Square` classes, which are drawn onto the canvas.

## Future Enhancements

- Add support for other shapes and colors.
- Implement user-friendly graphical user interface (GUI).
- Allow users to save and load drawings.
- Provide an option to export in different image formats.

## Acknowledgments

This project is inspired by programming exercises related to object-oriented programming, numpy, and image manipulation.

---
