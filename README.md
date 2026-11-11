# Signal and Image Processing with MATLAB

![MATLAB](https://img.shields.io/badge/MATLAB-R2022a-red)
![License](https://img.shields.io/badge/License-MIT-blue)

Hands-on lab materials for signal and image processing using MATLAB. Each module contains lab manuals, MATLAB Live Scripts (`.mlx`) with detailed description, and the sample data used in the exercises, along with a recorded lecture walking through the code.

I developed these labs for the undergraduate courses I taught in the Department of Electrical and Electronic Engineering at the Islamic University of Technology (IUT).

## Course structure

| # | Module | Topics | Lecture |
|---|--------|--------|---------|
| 01 | [Signal Processing](01-signal-processing/) | Signal generation and visualization, peak analysis, median and Hampel filtering | [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=37S29Pa6kMg) |
| 02 | [Digital Image Processing](02-digital-image-processing/) | Image basics and enhancement, histograms, segmentation, feature detection, image registration | [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=AKzelQ1HCRA) |
| 03 | [Biomedical Image Processing](03-biomedical-image-processing/) | Medical image enhancement, noise models, spatial filtering, edge detection | [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=tvMx2m45C_E) |

Module 02 introduces the core image processing ideas that Module 03 applies to medical images, so it's worth doing 02 first.

## Labs at a glance

### 01 – Signal Processing

| Lab | Live Script | Manual |
|-----|-------------|--------|
| Signal generation and visualization | [`signal_generation.mlx`](01-signal-processing/signal_generation.mlx) | [PDF](01-signal-processing/4.2%20signal%20generation%20manual.pdf) |
| Peak analysis | [`Find_Peaks.mlx`](01-signal-processing/Find_Peaks.mlx), [`Find_Peaks_2.mlx`](01-signal-processing/Find_Peaks_2.mlx) | [PDF](01-signal-processing/4.1%20peak%20analysis.pdf) |
| Filter operation (median, Hampel) | [`filter_op.mlx`](01-signal-processing/filter_op.mlx) | [PDF](01-signal-processing/4.3%20Filter%20operation.pdf) |

### 02 – Digital Image Processing

| Lab | Live Script | Manual |
|-----|-------------|--------|
| Basics, enhancement, histograms | — | [PDF](02-digital-image-processing/Digital%20Image%20Processing%20part_01.pdf) |
| Image segmentation (thresholding, concrete crack detection) | [`Image_Segmentation.mlx`](02-digital-image-processing/Image_Segmentation.mlx) | [PDF](02-digital-image-processing/Image_Segmentation.pdf) |
| Feature detection (corners, blobs, regions; Harris, SURF, MSER) | [`Detecting Features in images/`](02-digital-image-processing/Detecting%20Features%20in%20images/) | — |
| Image registration (pupil dilation from eye images) | [`Image_Registration/`](02-digital-image-processing/Image_Registration/) | — |

### 03 – Biomedical Image Processing

| Lab | Live Script |
|-----|-------------|
| 1. Image enhancement | [`1. Image enhancement.mlx`](03-biomedical-image-processing/1.%20Image%20enhancement.mlx) |
| 2. Image noise (Gaussian, Poisson, salt & pepper) | [`2. Image_noise.mlx`](03-biomedical-image-processing/2.%20Image_noise.mlx) |
| 3. Image filtering (low-pass, high-pass, median, Wiener) | [`3. Image_filter.mlx`](03-biomedical-image-processing/3.%20Image_filter.mlx) |
| 4. Edge detection (Canny, Sobel, LoG) | [`4. Edge detection.mlx`](03-biomedical-image-processing/4.%20Edge%20detection.mlx) |

Lab manual for the module: [Biomedical image processing.pdf](03-biomedical-image-processing/Biomedical%20image%20processing.pdf)

## Getting started

**Requirements**

- MATLAB R2022a or later
- Signal Processing Toolbox (Module 01)
- Image Processing Toolbox (Modules 02 and 03)
- Computer Vision Toolbox (feature detection labs in Module 02)

**Running the labs**

1. Clone the repository:
   ```bash
   git clone https://github.com/newaz-aa/Signal-and-Image-Processing.git
   ```
2. In MATLAB, set the current folder to the module you're working on (e.g. `02-digital-image-processing`) so the sample images and data files are found.
3. Open a `.mlx` file and run it section by section, following along with the PDF manual.

## License

Released under the [MIT License](LICENSE).
