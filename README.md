# Online Model Distillation for Efficient Video Inference

This public repository is currently a work in progress. Features currently supported include the JITNet architecture, pretraining on the COCO dataset, and model timing.

## Getting Started

Please install the following (Our versions shown in parentheses):

* Python 3, recommended through Anaconda (Python 3.6.5, Anaconda 4.5.11)
* CUDA and cuDNN (CUDA 9.2, cuDNN 7.3, NVIDIA-396 driver)
* Tensorflow (Tensorflow 1.10.1. We recommend to build from source for higher performance)

Clone this repository, then initialize submodules with `git submodule update --init --recursive`.

## Pretraining on the COCO Dataset

To pretrain JITNet on the COCO Dataset, first download and set up the COCO-stuff dataset from https://github.com/nightrome/cocostuff (TODO: detailed instructions)

TODO: detailed instructions on pretraining using the script.

## Timing the JITNet model

We include a timing script to determine JITNet inference time with different architecture setups and hardware/software configurations. Run it with `python utils/time_models.py`. The script times the default JITNet architecture setup: this can be changed by changing the 
arguments at the end of the script.

## Contact

Ravi Teja Mullapudi (rmullapu@cs.cmu.edu)

Steven Chen (stevenzc@stanford.edu) 
