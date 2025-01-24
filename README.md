# Rectangle Boundary Detection Without OpenCV

## Project Overview
This project demonstrates how to detect and visualize the boundaries of multiple rectangles drawn on a grid using only **NumPy** and **Matplotlib**. The goal is to replicate functionality typically handled by libraries like OpenCV while emphasizing fundamental computational techniques in Python.

### Features
- Draws multiple rectangles on a grid with clearly marked boundaries.
- Computes the contour (boundary points) of overlapping or adjacent rectangles.
- Visualizes the results:
  - Input rectangles with red edges.
  - Computed boundaries highlighted in blue.
- Outputs a list of boundary points in a readable format.

---

## Technologies Used
- **Python 3.8+**
- **NumPy:** Efficient matrix operations and array manipulation.
- **Matplotlib:** Visualization of the grid, rectangles, and contours.

---

## How It Works
1. **Input Rectangles:** Predefined set of rectangles specified by their coordinates `(x1, y1, x2, y2)`.
2. **Binary Mask Creation:** A blank grid is filled where rectangles are present.
3. **Boundary Detection:** Each pixel is checked for adjacency to empty (non-rectangle) space to identify boundary pixels.
4. **Contour Extraction:** The boundary pixels are collected as `(x, y)` coordinates.
5. **Visualization:**
   - Red edges depict the input rectangles.
   - Blue lines highlight the computed boundaries.

---

## Running the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/rectangle-boundary-detection.git
