# A Globally Convergent Gradient-based Bilevel Hyperparameter Optimization Method

## Required libraries
1. Tensorflow (Version>= 2.0)
2. Keras
3. Numpy
4. scikit-learn
5. Tensorflow Datasets
6. Matplotlib


## Steps to run the notebooks

1. Unzip the file
2. Folder structure is shown below


```
Root Directory
.
├── 1HP
│   ├── Bayesian Search
│   │   ├── Testing_of_SMBO_1k_60_40(1HP).ipynb
│   │   ├── Testing_SMBO_10k_60_40(1HP).ipynb
│   │   └── Testing_SMBO_5k_60_40(1HP).ipynb
│   ├── Datasets_10K
.
.
.
│   │   ├── Hyperband_10k_60_40(1HP).ipynb
│   │   ├── Hyperband_1k_60_40(1HP).ipynb
│   │   └── Hyperband_5k_60_40(1HP).ipynb
│   └── Testing Dataset
│       └── test_dataset.npz
└── 2HP
    ├── Bayesian Search
    │   ├── Testing_SMBO_10k_60_40(2HP).ipynb
    │   ├── Testing_SMBO_1k_60_40(2HP).ipynb
    │   └── Testing_SMBO_5k_60_40(2HP).ipynb
    ├── Dataset_10K
    │   ├── train_dataset_10k_60.npz
    │   └── validation_dataset_10k_40.npz
    .
    .
    .
    │   ├── GS_RS_1K_(60_40)2HP.ipynb
    │   ├── old_GS_RS_10K_(60_40)2HP.ipynb
    │   └── old_GS_RS_5K_(60_40)2HP.ipynb
    ├── HyperBand
    │   ├── Hyperband_10k_60_40(2HP).ipynb
    │   ├── Hyperband_1k_60_40(2HP).ipynb
    │   └── Hyperband_5k_60_40(2HP).ipynb
    └── Testing Dataset
        └── test_dataset.npz


```
3. Start the jupyter notebook server.
4. Navigate to desired notebook directory. Suppose you want to run 'Testing_of_SMBO_1k_60_40(1HP).ipynb' then change your directory to Bayesian Search i.e in ..../MNIST_MLP/1HP/Bayesian Search.
5. From the browser window select the notebook that you want to run.
6. Update the dataset path in the notebook and then run the cells.


## Citation

If you use this study, please cite below:

Sinha, A., Gunwal, S., & Kumar, S. (2023). A Globally Convergent Gradient-based Bilevel Hyperparameter Optimization Method. arXiv preprint arXiv:2208.12118. Retrieved from https://arxiv.org/abs/2208.12118

Repository Citation:

Sinha, A., Gunwal, S., & Kumar, S. (2024). A Globally Convergent Gradient-based Bilevel Hyperparameter Optimization Method (Version 1.0.0) [Computer software]. https://github.com/SGunwal/Bilevel_Hyperparameter_Optimization