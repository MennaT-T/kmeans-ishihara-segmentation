# kmeans-ishihara-segmentation

## 🧠 How It Works

This project implements the **K-Means clustering algorithm from scratch** and applies it to segment **Ishihara color blindness test images** to reveal the hidden numbers.

### Step-by-step process:
1. **Image Preprocessing**  
   The input image is loaded and reshaped into a 2D array of RGB pixels.

2. **K-Means Clustering**  
   Pixels are grouped into *k* clusters using a custom NumPy-based implementation of the K-Means algorithm.

3. **Cluster Extraction**  
   After clustering, one of the clusters representing the digits (based on color) is isolated and visualized. This makes the number inside the Ishihara plate much more visible.

---

## 🖼️ Example Results

Each image below shows the **original Ishihara test plate on the left**, and the **segmented number extracted using K-Means on the right**:

### `6.png`
![6](./6%20result.png)

### `12.png`
![12](./12%20result.png)

### `42.png`
![42](./42%20result.png)

### `74.png`
![74](./74%20result.png)
