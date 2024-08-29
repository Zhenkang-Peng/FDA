# FDA
This repository is intended to showcase the code used in the paper.

## Data
The **train.csv.zip** file contains the actual data used in our paper for comparing all methods. This dataset, sourced from a Kaggle competition, comes from Rossmann, a European pharmacy chain operating in seven countries. You can also access the dataset [here](https://www.kaggle.com/competitions/rossmann-store-sales).

## Code
1. **data_propressing.ipynb** is for data processing. The data processing methods described in the paper will be demonstrated and detailed in this Jupyter Notebook.
2. **all_methods.py**  contains all the algorithm functions mentioned in the paper, which are used by the main function. The algorithms include our proposed FDA linear and FDA tree methods, as well as other benchmark algorithms: Decoupled OLS, Shared OLS, DAC, Shrunken SAA, PAB linear, and PAB tree.
3. **main.ipynb** is the primary Jupyter Notebook used to demonstrate and execute various algorithms, as well as to calculate cost and runtime.
