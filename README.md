# bioRSP – Biological Radar Scanning Plots

bioRSP is a novel computational tool designed for analyzing and visualizing spatial patterns in multidimensional biological datasets. It offers a radar-like scanning mechanism that systematically evaluates data from various angles, uncovering complex heterogeneity and identifying potential biomarkers. bioRSP can be used in both qualitative (plot figures) and quantitative (RMSD, deviation) analyses, with applications in single-cell gene expression, spatial transcriptomics, and more.

## Features

- **Preprocessing:** Dimensionality reduction, clustering, and normalization techniques to prepare datasets for spatial analysis.
- **Visualization:** High-resolution radar-like plots for intuitive spatial pattern analysis.
- **Biomarker Identification:** Detects and highlights potential biomarkers based on gene expression patterns.
- **Community Detection:** Identifies subclusters within cell populations using spatial transcriptomics data.
- **Customizability:** Configurable parameters allow for tailored analysis to specific datasets and research questions.

## Installation

To install bioRSP, you can clone the repository and install the dependencies via pip:

```bash
git clone https://github.com/cytronicoder/biorsp.git
cd biorsp
pip install -r requirements.txt
```

## Usage

Here's a quick start guide to using bioRSP for your data:

1. **Preprocessing your data:** Ensure your data is in the correct format (single-cell, spatial transcriptomics, or differential gene expression data).
2. **Running bioRSP:** Once your data is preprocessed, run the following command to generate the radar scanning plots:

   ```python
   import bioRSP

   bioRSP.run_analysis(data, config)
   ```

3. **Visualizing results:** Use the built-in visualization tools to generate and customize the radar scanning plots.

4. **Analyzing biomarkers:** Utilize bioRSP's quantitative metrics (RMSD, deviation) to identify and interpret key biomarkers in your dataset.

More detailed documentation is available in the [wiki](https://github.com/cytronicoder/biorsp/wiki).

## Citation

If you use bioRSP in your work, please cite the bioRSP publication as follows:

> **Detecting Data Embedding Spatial Patterns and Identifying Biomarkers with BioRSP**
>
> Yao, Zeyu, and Jake Y. Chen
>
> _BioRxiv_ June 2024. doi: [10.1101/2024.06.25.599250](https://doi.org/10.1101/2024.06.25.599250).
