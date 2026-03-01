# SNEC
This repository contains the numerical data from the paper "Constraints on Genesis Cosmology from the Smeared Null Energy Condition" ([arXiv:2512.04934](https://arxiv.org/abs/2512.04934), DOI: [10.1103/ysm6-cq3k](https://doi.org/10.1103/ysm6-cq3k)).

We have open-sourced the data used to generate the figures in the paper. The data files are categorized into folders by their corresponding figure numbers (e.g., `Fig1`, `Fig2`, etc.). The colors in the data filenames (e.g., Blue, Green, Red, Gray) correspond to different parameter benchmark points as described in the paper.

## Data Structure and RegionPlot Boundaries

All data files are provided in `.xlsx` format. For every file, the data structure is standardized as follows:
* **Column A (First Column):** Represents the x-axis variable.
* **Column B (Second Column):** Represents the y-axis variable.

**Important Note on Data Points:**
The figures in the paper are `RegionPlot`s showing excluded parameter spaces (shaded regions). Since it is impractical to provide every single coordinate point within a 2D shaded region, **the data provided here represents the exact boundary lines of these regions.**

## Naming Conventions and Variables

### Figure Panels (`left` and `right`)
For figures that contain multiple subplots (panels), we use `left` and `right` in the filenames to distinguish them. For example, `FIG2-left-Green.xlsx` corresponds to the green boundary line in the left panel of Figure 2.

### Axes Variables by Figure
* **Fig 1, Fig 2, and Fig 3:**
    * x-axis (Column A): Smearing width ($\Delta t$)
    * y-axis (Column B): The parameter combination ($\Lambda$)
* **Fig 4, Fig 5, and Fig 6:**
    * x-axis (Column A): Parameter ($\gamma$)
    * y-axis (Column B): Parameter ($\kappa$)

## Contact
If you have any questions or are interested in related fields, please contact caiyong@zzu.edu.cn.
