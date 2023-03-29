# Segmentation and feature extraction using CellProfiler

In this module, we segment nuclei, cytoplasms, and whole cells from images and perform feature extraction using CellProfiler.

## Run the `nf1_analysis` notebook

To run the CellProfiler analysis pipeline on the illumination corrected images for each plate, run the [nf1_analysis.ipynb](nf1_analysis.ipynb) notebook as a python script using the code block below:

```bash
# Run this script in terminal
# move to the 2.cellprofiler_analysis directory to access the `sh` script
cd 2.cellprofiler_analysis
# run the notebook as a python script
bash nf1_analysis.sh
```
