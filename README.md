OpenCV Demo

A hands-on walkthrough of core OpenCV image processing operations using Python. Covers reading/displaying images, resizing, color space conversion, drawing shapes, blurring, edge detection, thresholding, morphological transformations, and contour detection.

Features


Image I/O & Resizing load and resize images
Color Space Conversion — BGR → Grayscale, BGR → HSV
Drawing Functions — lines, rectangles, circles, text overlays
Blurring — Average, Gaussian, Median, Bilateral filters
Edge Detection — Canny, Sobel X/Y, Laplacian
Thresholding — Simple, Otsu, Adaptive Mean, Adaptive Gaussian
Morphological Transformations — Erosion, Dilation, Opening, Closing
Contour Detection — find and draw external contours


Requirements

opencv-python
numpy
matplotlib

Install with:

bashpip install -r requirements.txt

Usage

Place an image in the project folder (default name: sample.jpg), then run:

bashpython cv_unnati.py

Or specify a custom image path:

bashpython cv_unnati.py path/to/your/image.jpg

Each processing step opens as a separate matplotlib window — close one to move to the next.

Notes


Requires an image file to run; the script will raise a clear error if the image path is invalid.
Built and tested with OpenCV 5.0.0.


License

MIT