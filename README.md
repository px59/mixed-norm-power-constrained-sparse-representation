## GPU Accelerated PCSR implementation with Python
## *Power-Constrained Image Contrast Enhancement Through Sparse Representation by Joint Mixed-Norm Regularization*
Jia-Li Yin, Bo-Hao Chen, En-Hung Lai, and Ling-Feng Shi

![](/demo.png)

## Prerequisites:
> * Linux
> * Anaconda
> * CUDA 9.2
> * cuDNN 7.2.1
> * Numbapro 0.23.1
> * Python 2.7
> * Numpy 1.10.4
> * pip 19.1.1
> * OpenCV 3.4.1

## It was tested and runs under the following OSs:
* Ubuntu 18.04
* Ubuntu 16.04

Might work under others, but didn't get to test any other OSs just yet.

## Getting Started:
### Installation
- create a PCSR environment
```bash
conda create -n PCSR numbapro
```
- activate the PCSR environment
```bash
source activate PCSR
```
- install opencv
```bash
conda install opencv 
```
- install python-spams
```bash
conda install -c conda-forge python-spams
```

### Testing 
- To test the PCSR model:
```bash
python main.py
``` 
The test results will be saved in: `./Results/.`

## Citation:   
    @ARTICLE{yin2019PCCE, 
    author={J. {Yin} and B. {Chen} and E. {Lai} and L. {Shi}}, 
    journal={IEEE Transactions on Circuits and Systems for Video Technology},  
    title={Power-Constrained Image Contrast Enhancement Through Sparse Representation by Joint Mixed-Norm Regularization},  
    year={2020},  
    volume={30}, 
    number={8},  
    pages={2477-2488},}
