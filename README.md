
# Image Filtering and Evaluation Using MSE

Welcome to the **Image Filtering and Evaluation Using MSE** project! This repository demonstrates how to apply various filters to images, convert BMP images to JPG format, and evaluate the effectiveness of these filters using Mean Squared Error (MSE).

## Introduction

This project showcases a method to apply different image filters and assess their effectiveness using MSE. It aims to help users understand how different filters impact the quality and features of images, and how to select the best filters for their specific needs.

## What is Mean Squared Error (MSE)?

Mean Squared Error (MSE) is a metric used to measure the average squared difference between the original and filtered images. A lower MSE value indicates that the filtered image is more similar to the original image, whereas a higher MSE value indicates a greater difference.

## How to Find the Best Filters for Further Processing?

To find the best filters for further processing, you can apply various filters to the images and calculate the MSE for each filter. By comparing the MSE values, you can determine which filters preserve the most detail or achieve the desired effect with minimal alteration to the original image.

## Applying and Evaluating Filters

This project includes a Jupyter notebook that demonstrates the following steps:

1. **Convert BMP Images to JPG Format**:
   - The notebook includes a function to convert BMP files to JPG format.

2. **Apply Selected Filters**:
   - Various filters such as Gaussian Blur, Median Blur, Bilateral Filter, Sharpen, Emboss, Sepia, Negative, and more are applied to the images.

3. **Evaluate Filters Using MSE**:
   - The effectiveness of each filter is evaluated using the Mean Squared Error (MSE) metric.

4. **Save Filtered Images with MSE Values**:
   - The filtered images are saved as a single subplot image with MSE values included in the titles.

## Repository Contents

- `main.ipynb`: The Jupyter notebook containing the code for applying and evaluating image filters.
- `example_images/`: A directory containing example BMP images (ensure this directory exists with BMP images for the notebook to process).
- `output_images/`: A directory where the output subplot images will be saved (ensure this directory exists for saving output).

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- OpenCV
- NumPy
- Matplotlib
- os

You can install the required libraries using pip:

```bash
pip install opencv-python numpy matplotlib
```

### Running the Notebook

1. Clone this repository to your local machine:

```bash
git clone https://github.com/lvimuth/ImageFilterExperiments.git
```

2. Navigate to the project directory:

```bash
cd ImageFilterExperiments
```

3. Open the Jupyter notebook:

```bash
jupyter notebook ImageFilterExperiments.ipynb
```

4. Run the notebook cells to convert BMP images to JPG, apply filters, evaluate them using MSE, and save the results.

## Example Results

![Example Subplot](https://github.com/lvimuth/ImageFilterExperiments/blob/main/PlotImg/houses_subplot.jpg)

The example above shows the original image and various filtered images with their corresponding MSE values.

## Contributing

We welcome contributions! If you have suggestions or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
