# AnoGAN keras implementation

Unsupervised anomaly detection with DCGAN

## Usage  

First, check directory structure

    ├── main.py
    ├── anogan.py 
    ├── weights
        ├── discriminator.h5
        └── generator.h5
    └── result
        └── save the generated images when training

To test this project

    $ python main.py


To train a model

    $ python main.py --mode train

Then, the training steps(image) will be saved 'result' directory


-----------

    usage: main.py [-h] [--img_idx IMG_IDX] 
                        [--label_idx LABEL_IDX] 
                        [--mode MODE]


### Reference

paper : https://arxiv.org/abs/1703.05921 <br>
code : https://github.com/tkwoo/anogan-keras <br>
