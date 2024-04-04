# ztem_simpeg
ZTEM forward modeling and inversion in SimPEG as part of UBC course EOSC 556B using synthetic and field data. 

- `notebooks` contains the forward and inversion steps for synthetic are split over two jupyter notebooks. 
- `data` includes the exported forward modelled data as well as the model and mesh files for the same.
`field` subfolder within the `data` folder includes the field dataset as described here: https://giftoolscookbook.readthedocs.io/en/latest/content/comprehensive_workflow/joint_mt_ztem/index.html
- `inv_models` folder contains the recovered models for each iteration of inversion.


The cuurent notebooks model and invert for three frequencies (30 Hz, 45 Hz, 90 Hz) only due to computational/time constraints. 

- <ztem_syn_fwd_full.ipynb> contains the forward model for a synthetic L-shaped model.
- <ztem_syn_inv_full.ipynb> contains the inversion for the synthetic L-shaped model.
- <ztem_true.ipynb> is currently incomplete. It will contains the inversion for field dataset.

TODO:: 
- Add notebook with decimated mesh and freqs so they can run on laptop. 
- Update field data notebook. 
- Add tests.
