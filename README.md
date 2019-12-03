**CSC420 Final Project**

For our final project, we implemented the DnCNN architecture by Zhang et al. [1].

**How to run**

Load the .ipynb file into Google Colab.

Run the main function. You must include root_dir as the first argument which is the root location of the dataset path. You may pass in optional arguments to the main function to override their default values:

- num_epochs=50
- num_layers=17
- num_channels=3
- batch_size=1
- lr=1r-3
- augment=False
- save=False
- noise='gaussian'
- filter='gaussian'


**References**

[1] K. He, X. Zhang, S. Ren, and J. Sun, “Deep residual learning for image recognition,” *arXiv preprint arXiv:1512.03385, 2015.*
