# EMS741 - Deep Learning for Data and Image Analysis

A repository that contains tutorials, datasets and other resources for the EMS741 (Deep Learning for Data and Image Analysis) module at Queen Mary University of London.

## Teaching Team:

- Claire Villette (c.villette@qmul.ac.uk) - Module Organiser and Lecturer
- Shaheer U. Saeed (shaheer.saeed@qmul.ac.uk) - Lecturer
- TBD - Teaching Associate

## Code Requirements:

Tutorials, lab sessions and coursework all use Jupyter notebooks in [Google Colab](https://colab.research.google.com/). All ipynb files in this repository can be uploaded into Google Colab and accessed interactively. By default, all uploaded notebooks are saved into your Google Drive, so if you need to find one again, please refer to the correct Google Drive folder as opposed to uploading the same notebook again.

For any notebooks that you use as part of this module, please ensure that the first cell downloads the requisite data and installs the required python packages. Refer to the `intro_to_python` tutorial in the repository for further details. A minimal example is provided below:

```
!pip install torch tensorflow matplotlib nibabel
!wget -O data.zip https://github.com/s-sd/EMS741/raw/refs/heads/main/tutorials/intro_to_python/data.zip

import nibabel as nib
import numpy as np
import matplotlib.pyplot as plt
import os
```


