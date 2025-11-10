## Image to Pencil Sketch Converter 

A clean, beginner-friendly Python project that transforms any photo into a realistic pencil sketch using OpenCV.
### Project Overview
Developed a Python application that converts a colored image into a high-quality pencil sketch.  

### How It Works (The Magic Behind the Sketch)
The algorithm uses the classic **dodge-blend technique**:
1. Read the image in RGB  
2. Convert to grayscale  
3. Invert the grayscale image  
4. Apply Gaussian blur to the inverted image  
5. Invert the blurred image again  
6. Divide original grayscale by the inverted-blurred image → **Pencil Sketch**

Result? A clean, artistic sketch that actually looks hand-drawn!


### Requirements
```bash
opencv-python>=4.5
```

Install with:
```bash
pip install opencv-python
```

---

### How to Run (Super Easy)
```bash
git clone https://github.com/mahimajai/IMAGE-TO-PENCIL-SKETCH

cd IMAGE-TO-PENCIL-SKETCH

Then open `IMAGE TO PENCIL SKETCH.ipynb` in:
- Jupyter Notebook
- VS Code

**Steps inside the notebook:**
1. Upload your own photo (or use the sample one)
2. Run all cells
3. Download `sketch_output.jpg`

Done! Your pencil sketch is ready in under 9 seconds.


### Features
- Zero dependencies except OpenCV  
- Works offline  
-  fast (less then 10 second)  
- Adjustable blur intensity (tweak σ for thinner/thicker lines)  
- Supports JPG, PNG, any resolution  

