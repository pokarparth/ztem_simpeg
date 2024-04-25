# Inverting synthetic and field ZTEM data using SimPEG [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pokarparth/ztem_simpeg/main)

## Objective
ZTEM forward modeling and inversion in SimPEG as part of UBC course EOSC 556B using synthetic and field data. 

The primary objective is to invert field ZTEM dataset to check capabilities of SimPEG and comparing the results with those produced using UBC-GIF codes. 

A secondary objective is for this notebook to be a starting template for running future Natural Source EM inversions.


## Content 
- `notebooks` contains the forward and inversion steps for synthetic are split over two jupyter notebooks. 
- `data` includes the exported forward modelled data as well as the model and mesh files for the same.
`field` subfolder within the `data` folder includes the field dataset as described here: https://giftoolscookbook.readthedocs.io/en/latest/content/comprehensive_workflow/joint_mt_ztem/index.html
- `inv_models` folder contains the recovered models for each iteration of inversion. 


- `ztem_syn_fwd_full.ipynb` contains the forward model for a synthetic L-shaped model.
- `ztem_syn_inv_full.ipynb` contains the inversion for the synthetic L-shaped model.
- `ztem_true_deci.ipynb` contains the inversion for field dataset. 

## TODO 
- Add tests.

## Installation instructions

**Note**: At least 16GB of RAM is recommended for running the synthetic examples and 128 GB RAM is recommended for running the field example notebook.

To run the project, follow these installation instructions:

1. Clone the repository or download as zip file:
    ```
    git clone https://github.com/pokarparth/ztem_simpeg
    ```

2. Navigate to the project directory:

    ```
    cd ztem_simpeg
    ```

3. Create a conda environment using the provided environment.yml file:

    ```
    conda env create -f environment.yml
    ```

4. Activate the conda environment:

    ```
    conda activate ztem-simpeg
    ```

5. Run the notebooks.

## License 

This repo is licensed under MIT terms. Feel free to use or modify it as needed. 

Please open an issue or PR with any modifications, suggestions, or questions!
