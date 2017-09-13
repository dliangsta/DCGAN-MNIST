# DCGAN-MNIST

### Overview
Deep Convolutional Generative Adversarial Network implementation for generating MNIST handwritten digits, based on [this paper](https://arxiv.org/abs/1511.06434). Project by [dliangsta](https://github.com/dliangsta), [sahibgoa](https://github.com/sahibgoa), [vperiyasamy](https://github.com/vperiyasamy), [shantanusinghal](https://github.com/shantanusinghal), and [evanfredhernandez](https://github.com/evanfredhernandez).

### Results

Progression of samples as DCGAN is trained: <br/>
![1 epoch](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_000.jpg)
![10 epochs](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_010.jpg)
![20 epochs](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_020.jpg)
![30 epochs](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_030.jpg)
![40 epochs](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_040.jpg)
![50 epochs](https://github.com/dliangsta/DCGAN-MNIST/blob/master/samples/sample_050.jpg)


### Dependencies

python3, tensorflow-gpu, numpy, scipy

### Usage

```
usage: python3 src/main.py [-h] [--data_dir DATA_DIR] [--learning-rate LEARNING_RATE]
               [--decay-rate DECAY_RATE] [--batch-size BATCH_SIZE]
               [--num-epochs NUM_EPOCHS] [--out OUT]

optional arguments:
  -h, --help            show this help message and exit
  --data_dir DATA_DIR   Directory for storing input data
  --learning-rate LEARNING_RATE
                        the learning rate for training
  --decay-rate DECAY_RATE
                        the learning rate for training
  --batch-size BATCH_SIZE
                        the batch size
  --num-epochs NUM_EPOCHS
                        number of epochs
  --out OUT             output location for writing samples from G
```
