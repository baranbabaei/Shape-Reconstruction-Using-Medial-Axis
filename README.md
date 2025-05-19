# 🧩 Shape Reconstruction Using Medial Axis

This project implements shape reconstruction using **medial axis extraction** from 2D and 3D point sets. The method is applied through skeletonization and Voronoi-based medial axis calculation, followed by shape visualization.

## 📁 Project Contents

- `horse-2D.txt`: Input point cloud data for a 2D horse shape.
- `skeletonioze_medial_axis_2d.py`: Extracts the medial axis (skeleton) of a 2D shape using pixel-based skeletonization.
- `voronei_medial_axis_2d.py`: Computes medial axis using **Voronoi diagrams**.
- `plot_3d.py`: Visualizes 3D shape data and medial axis.
- `Voronoi.png`, `Skeletonize.png`, `Plot3D.png`: Sample output images.
- `notebook.pdf`: Final report explaining the algorithms and results.

## 🧠 Algorithms & Techniques

- **Skeletonization**: Thin the shape to its central axis using morphological image processing.
- **Voronoi-based Medial Axis**: Use Voronoi tessellation to find equidistant skeletal points.
- **Delaunay Triangulation**: (Described in the report) used for reconstructing the original geometry.

## 🛠️ Technologies Used

- Python 3.x
- NumPy
- Matplotlib
- SciPy
- scikit-image

## 🚀 How to Run the Project

1. **Install Required Libraries**

   ```bash
   pip install numpy matplotlib scipy scikit-image
   ```

2. **Run 2D Skeletonization**

   ```bash
   python skeletonioze_medial_axis_2d.py
   ```

3. **Run Voronoi-based Medial Axis**

   ```bash
   python voronei_medial_axis_2d.py
   ```

4. **Run 3D Visualization**

   ```bash
   python plot_3d.py
   ```

## 📊 Sample Outputs

- `Voronoi.png`: Medial axis using Voronoi diagram
- `Skeletonize.png`: Skeletonization result of the 2D shape
- `Plot3D.png`: 3D plot visualization

## 📂 Folder Structure

```
shape-reconstruction/
│
├── horse-2D.txt
├── skeletonioze_medial_axis_2d.py
├── voronei_medial_axis_2d.py
├── plot_3d.py
├── Voronoi.png
├── Skeletonize.png
├── Plot3D.png
└── README.md
```

## 👩‍💻 Authors

- **Baran Babaei**
- **Poroshat Rahmani**
- **Alireza Dolatabadi**

