# Data Preparing

#### 1. Access to the iCTCF dataset: https://ngdc.cncb.ac.cn/ictcf/HUST-19.php
#### 2. Use the methods illustrated in [1] to preprocess the data.

[1] Bao, G., Chen, H., Liu, T., Gong, G., Yin, Y., Wang, L., Wang, X.: Covid-mtl: Multitask learning with shift3d and random-weighted loss for covid-19 diagnosis and severity assessment. Pattern Recognition 124, 108499 (2022) 6

#### 3. Sort out the data and code:
```bash
.
├── code
│   ├──datasets
│   │       └── dataset_*.py
│   ├──train.py
│   ├──test.py
│   └──...
├── models_save
│   └── iCTCF
└── data
    └──Synapse
        ├── iCTCF_train
        │   ├── Patient-1.npy.h5
        │   └── *.npy.h5
        └── iCTCF_test
            ├── Patient-1000.npy.h5
            └── *.npy.h5
```

#### 4. Training
```bash 
python train.py
```

#### 5. The used packages:
```bash
Package                Version
---------------------- -------------------
h5py                   3.1.0
numpy                  1.19.5
opencv-python          3.4.0.12
pandas                 1.1.5
SimpleITK              1.2.4
sklearn                0.0
torch                  1.6.0
torchvision            0.7.0
```



