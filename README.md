# Human-Action-Recognition-Visualization-using-Isomap-Manifold-Learning-
This project applies Isomap, a nonlinear dimensionality reduction technique, to visualize human action image data. It includes feature extraction from images, PCA for noise reduction, and an interactive Bokeh visualization where users can hover over points to view actual images and activity labels


## 🎨 Interactive Visualization (Bokeh)

This project uses **Bokeh** to create an interactive visualization of Isomap embeddings.

### ✨ Features:

* Hover over points to see:

  * Image thumbnail 🖼️
  * Activity label
* Color-coded clusters for different actions
* Smooth and interactive exploration of data

### 🧠 Why Bokeh?

* Provides real-time interactivity
* Enhances understanding of clusters
* Makes the project visually professional

---
## ⚙️ Technical Details

### 🔹 Feature Extraction

* Images converted to grayscale
* Resized to 64x64
* Flattened into feature vectors

### 🔹 Preprocessing

* StandardScaler used for normalization

### 🔹 Dimensionality Reduction

* PCA applied for noise reduction (300 components)
* Isomap applied for nonlinear embedding (5 components)

### 🔹 Visualization

* Bokeh used for interactive plotting
* Hover tool displays image + label

### 🔹 Evaluation

* Silhouette Score used to measure clustering quality

---
## 🖼️ Image Hover Feature

Each data point in the visualization represents an image.

When hovering over a point:

* The corresponding image is displayed
* The activity label is shown

This helps in:

* Understanding cluster composition
* Identifying misclustered samples
* Visually validating model behavior

---
<img width="1352" height="650" alt="image" src="https://github.com/user-attachments/assets/bb47a3c2-96ab-465b-8457-e3868e39c926" />

