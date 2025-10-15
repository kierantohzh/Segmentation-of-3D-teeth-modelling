# Region Fusion Image Segmentation

This project implements a **Region Fusion** algorithm for image segmentation based on intensity similarity and spatial connectivity. It is inspired by the L0 gradient minimization and region fusion approaches used in image processing literature.

The goal is to merge similar regions in a grayscale image while preserving edges and structural boundaries.

---

## Features

- Initializes each pixel as its own region.
- Computes connection numbers between neighboring regions (4-connectivity).
- Computes a **fusion cost** that balances intensity similarity and boundary penalties.
- Iteratively merges regions with negative fusion cost.
- Produces a segmented image with merged regions of similar intensity.
- Simple, efficient, and easy to understand implementation in Python using NumPy.

---

## Requirements

- Python 3.7+
- Libraries:
  ```bash
  pip install numpy
