# OpenCV Examples

Small Python scripts I wrote while learning the basics of OpenCV: reading images and videos, drawing on images and simple image processing.

## Scripts

All scripts are in the `code/` folder.

| Script | What it does |
|--------|--------------|
| `read.py` | Plays `doggy.mp4` frame by frame next to a rescaled copy (`rescaleFrame`). Also has `changeRes` for setting the resolution of a live camera feed. Press **d** to stop. |
| `draw.py` | Creates a blank 500×500 image and paints a coloured region, a rectangle, a circle and some text on it. |
| `basic.py` | Runs a set of basic operations on `park.jpg`: grayscale conversion, Gaussian blur, Canny edge detection, dilation, erosion, resizing and cropping. Each result opens in its own window. |

## Sample media

- `images/`: `park.jpg`, `cat.jpg`, `kitty.jpg`
- `videos/`: `doggy.mp4`

## Running

```bash
pip install opencv-python numpy
```

The scripts open files by name only (for example `cv.imread('park.jpg')`), so the image or video needs to be in the folder you run the script from:

```bash
cd images
python ../code/basic.py
```

Press any key to close the windows.
