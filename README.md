# Pancreas Segmentation from CT Scans

This repository contains the code and dataset used in an IRB-approved study for the segmentation of the pancreas from portal venous phase CT scans. The project involved training technologists to segment the pancreas using advanced image-viewing software and was supplemented by multimedia instructional content to enhance segmentation accuracy.

## Project Overview

This project aims to develop and validate an automated tool for pancreas segmentation by:
- Training technologists through radiologist-led sessions.
- Using freehand tools on custom image-viewing software to segment the pancreas.
- Enhancing the accuracy of these segmentations through additional multimedia training.
- Evaluating segmentations using metrics like Dice-Sorenson coefficient (DSC), Jaccard coefficient (JC), and Bland–Altman analysis.

## Dataset

The dataset includes 347 CT scans, segmented and annotated. Features include:
- RGB values for each pixel.
- Mean and standard deviation for Red, Green, and Blue color channels.
- Segmentations reviewed and corrected by two expert radiologists.

### Data Description

- `initial_segmentation/`: Contains the initial batch of 188 CT segmentations.
- `supplementary_segmentation/`: Contains the second batch of 159 CT segmentations after additional training.
- `rgb_data/`: RGB codes and statistical data derived from the segmented images.

## Getting Started

### Prerequisites

- Python 3.8+
- Libraries: numpy, matplotlib, shap, sklearn (See `requirements.txt` for more details)

## Contributing
Contributions to this project are welcome! Here are a few ways you can help:

## Improve the segmentation algorithms.
Enhance the training material for technologists.
Update the documentation.
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
Thanks to the radiologists and technologists who contributed to the training and validation phases.
Special thanks to Lundberg and Lee for the development of the SHAP library, which enhanced our understanding of feature contributions.
