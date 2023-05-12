# Point Cloud Segmentation and Visualization

![results 1](https://raw.githubusercontent.com/rehmantalha1999/part_segmentation/main/results%201.png)
![results 2](https://raw.githubusercontent.com/rehmantalha1999/part_segmentation/main/results%202.png)
![results 3](https://raw.githubusercontent.com/rehmantalha1999/part_segmentation/main/results%203.png)
![results 4](https://raw.githubusercontent.com/rehmantalha1999/part_segmentation/main/results%204.png)
![results 5](https://raw.githubusercontent.com/rehmantalha1999/part_segmentation/main/results%205.png)

This repository contains a Python implementation for segmenting and visualizing point clouds using RANSAC, curvature-based filtering, and outlier removal techniques. The implementation is tested with the following library versions:

- Open3D 0.12.0
- NumPy 1.20.3
- SciPy 1.6.3
- Scikit-learn 0.24.2
- Plotly 4.14.3
- Numba 0.53.1

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Requirements](#requirements)
- [Example Datasets](#example-datasets)
- [Troubleshooting and FAQ](#troubleshooting-and-faq)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Introduction

This implementation provides an efficient and customizable way to segment and visualize point clouds, especially for 3D objects with complex geometries. The main steps of the process are:

1. Sampling points uniformly from a mesh
2. Computing and filtering points based on their curvature
3. Removing outliers
4. Applying RANSAC-based segmentation
5. Merging small segments and visualizing the results

## Installation

To install the required libraries, run:

pip install open3d numpy scipy scikit-learn plotly numba


## Usage

To use the implementation, follow these steps:

1. Clone this repository:

git clone https://github.com/rehmantalha1999/part-segmentation.git
cd point-cloud-segmentation

2. Modify the `main.py` script to process your point cloud data, adjusting parameters as needed.
3. Run the `main.py` script:

4. Visualize the results using the provided visualization functions.

## Results

The implementation produces a segmented point cloud with unique colors assigned to each segment. The high-curvature points and outliers are removed, resulting in a cleaner representation of the input point cloud.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Requirements

### Hardware:

- CPU: Intel Core i5 or equivalent
- RAM: 8 GB
- GPU (optional): NVIDIA CUDA compatible

## Example Datasets

To help users get started with the implementation, you can provide a few example datasets (3D models or point clouds) and their expected results. This section can describe the datasets and include links to download them.

## Troubleshooting and FAQ

This section can include a list of common issues that users may encounter when running the implementation and their respective solutions. You can also add frequently asked questions about the implementation, its usage, and customization.

## Contributing

If you would like to encourage collaboration on the project, you can add guidelines for users to contribute. This section can include information on how to report issues, submit pull requests, and propose new features.

## Acknowledgements

In this section, you can acknowledge and provide references to the original research papers, articles, or other sources that inspired or contributed to the development of this implementation.

## Contact

If you have any questions or suggestions, feel free to reach out to me or my company:

- Name: Talha Rehman Abid
- Position: Data Science Intern
- Email: rehmantalha.yt@gmail.com
- Company: [Dakik Yazilim](https://www.dakikyazilim.com/)
- LinkedIn: [Talha Rehman Abid](https://www.linkedin.com/in/talha-rehman-abid-b46900214/)
