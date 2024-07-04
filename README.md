# Uncovering Biological Insights in Spatial Transcriptomics Data in Mouse Brain Aging

Author: Arya Bakhtiar

This project is connected to the osNMF project: Unsupervised pattern discovery in spatial gene expression atlas reveals mouse brain regions beyond established ontology.

The spatial transcriptomics data and other support files for this project exceeds > 50GB in size. Please reach out for further inquiry on the project. 

Manuscript link to the osNMF Project on BioRxiv: https://www.biorxiv.org/content/10.1101/2023.03.10.531984v1

## Background

Project involves using tools such as deep autoencoders, non-negative matrix factorization (NMF) and semi-supervised deep convolutional neural networks to find meaningful gene expression patterns in these images. 

- 4,345 genes at 200 µm isotropic resolution from the adult mouse brain at 56 days postnatal
-- Source: Allen Institute for Brain Science (ABA)
- Each Gene was associated with a 67x41x58 matrix representing 3D mouse brain
- The Allen Mouse Brain Common Coordinate Framework (CCF) was used as the 3D reference atlas

## Requirements

Python 3.9

Python packages: matplotlib, napari, networkx, nrrd, numpy, os, pandas, pickle, sklearn

## osNMF Support Code
https://github.com/abbasilab/osNMF

<!-- LICENSE -->
## License

Distributed under the License. See `LICENSE` for more information.

## Version
Last update: September 2023
