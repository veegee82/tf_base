## Tensorflow Base Library

The tf_base library is a package that includes basic functionalities that help users to quickly and efficiently train models and try new approaches. It contains basic functionalities for cost functions, normalization, activation functions and various layers. In addition, interfaces for models, as well as an entire pipeline, are provided for training and inferencing structures, which allows the loading of data. An example of this pipeline can be found under ./example.

## Pre-requiremtents
* tensorflow >= 1.8 
* pil 
* numpy 
* opencv

## Installation 
1. Clone the repository
```
$ git clone https://github.com/Shumway82/tf_base.git
```
2. Go to folder
```
$ cd tf_base
```
3. Install with pip3
```
$ pip3 install -e .
```

## Usage-Example
```python
import tfcore 
from tfcore.interfaces.ITraining import *
```

## Licensing
tf_core is released under the MIT License (MIT), see LICENSE.
