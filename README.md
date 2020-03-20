# LG-ER-MT
Model for reproducing experimental results. Code will be released soon.

### Installation
This repository is based on PyTorch 0.4.1.

### Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/3DMRIs/LG-ER-MT.git
   cd LG-ER-MT
   ```
2. Download dataset
   ```shell
   Please download Atrial Segmentation Challenge dataset (https://atriaseg2018.cardiacatlas.org/)
   Put the data in `data/2018LA_Seg_TrainingSet`.
    ```
3. Test the model:
 
   ```shell
   cd code
   python test_LA.py --gpu 0
   ```
