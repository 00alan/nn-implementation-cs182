## Implementing and training nn and cnn. cs182

#### env creation for running assignment 1 and 2 locally:

- install pytorch and torchvision from pytorch channel

- then install (some redundancy with pytorch but is okay):
numpy matplotlib pillow scipy h5py scikit-image cython imageio jupyter nltk

- if certain data files are missing, may need to run certain bash scripts in the /datasets directories

- for cython issues in assignments 1 and 2, run the following from /deeplearning directories and restart kernel:
python setup.py build_ext --inplace 

- for character encoding issues visit charset_decoder.py file

- assignment2 extra credit takes a while
