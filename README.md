# introduction-to-portable-imaging-EEG

The Jupyter notebook in this repo contains scripts for the Vandy BrainHacks EEG tutorial on January 20, 2024.

Before you run this, please make sure the .ipynb file is in the same location as a directory called `data` containing the `MMN_Practice.set` file (available on the Google Drive, since it was too large to host on GitHub) and a subdirectory called `openneuro-downloads`.

All of the code in this tutorial is mine, but the datasets are not. The resting-state dataset (which we'll download from openneuro.com) is from:

Hatlestad-Hall, C., Rygvold, T. W., & Andersson, S. (2022). BIDS-structured resting-state electroencephalography (EEG) data extracted from an experimental paradigm. Data in Brief, 45, 108647. https://doi.org/10.1016/j.dib.2022.108647

and the ERP dataset (in the `MMN_Practice.set` file) is from:

Garrido, M. I., Kilner, J. M., Kiebel, S. J., Stephan, K. E., & Friston, K. J. (2007). Dynamic causal modelling of evoked potentials: a reproducibility study. NeuroImage, 1;36(3):571-8 https://doi.org/10.1016/j.neuroimage.2007.03.0140.