## Pencil Sketch Filter (Python & OpenCV)

This Python script, using OpenCV, applies a cool pencil sketch effect to an image.

**Features:**

* Loads an image (assumes "dog.jpeg" exists in the same directory).
* Converts to grayscale and inverts.
* Applies Gaussian blur for smoothing.
* Creates a pencil sketch by dividing grayscale by inverted blurred image.
* Displays both original and sketch images side-by-side.

**Requirements:**

* Python 3
* OpenCV library (install with `pip install opencv-python`)

**Usage:**

1. Save the script as `pencil_sketch.py`.
2. Place "dog.jpeg" (or your desired image) in the same directory.
3. Run the script: `python pencil_sketch.py`.

**Enjoy your sketch!**

**Bonus:**

* Experiment with different blur kernel sizes and scaling factors for the sketch effect.
* Adapt the code to work with other image formats and file names.
