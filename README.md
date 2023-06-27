# Implementing and training nn and cnn. cs182

### env creation for running locally:

- install pytorch and torchvision from pytorch channel

- then install (some redundancy with pytorch but is okay):
numpy matplotlib pillow scipy h5py scikit-image cython imageio jupyter nltk

- I used mamba, and python 3.11 (installed by pytorch by default)

### potential issues

- if certain data files are missing, may need to run certain bash scripts in the /datasets directories

- for cython issues, run the following from /deeplearning directories and restart kernel:
python setup.py build_ext --inplace 

- for character encoding issues visit charset_decoder.py file
