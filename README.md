# P-INT


## Start

### Requirements
* ``Python 3.7.9 ``
* ``PyTorch 1.7.0``

### Datasets
We conduct our experiments on two datasets — NELL-One and FB15k237-One. 
You can find original datasets(NELL-One) from [here](https://github.com/xwhan/One-shot-Relational-Learning).

You can download datasets used in this work from [here](https://drive.google.com/drive/folders/16pamNJ-8gDPC2qaObN0pr93xeqdzq4Sq?usp=sharing)

### Training
* For NELL-One: python train.py --dataset "NELL-One" --few n --max_batches 200000
* For FB15k237-One: python train.py --dataset "FB15k237-One" --few n --max_batches 10000

### Test
* For NELL-One: python train.py --dataset "NELL-One" --few n --test
* For FB15k237-One: python train.py --dataset "FB15k237-One" --few n --test

