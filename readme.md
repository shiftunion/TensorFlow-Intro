## Some notes
Tensor's are N Dimensial Arrays - defining whatever! They flow through operations. Tensor's can also be simple types

### Mac Install
https://www.tensorflow.org/install/install_mac
Follow instrcution for `virtualenv`

Activate a virtual env
```source ~/tensorflow/bin/activate```

Deactivate virtual env
```(tensorflow)$ deactivate```

### Get MacOSX matplotlib working

```
import matplotlib as mpl
mpl.use('TkAgg')
```

### Local Docker install
Gets a local TensorFlow docker continer running with a shared local volume

`docker run -v ~/dev/tensorflow/intro:/intro -it jupyter/tensorflow-notebook bash`

### Tensor Dimensions
#### Rank 
0 = Scalar
1 = Vector [1,2,5,7]
2 = Matrix [[1,2,3],[6,8,9]]
3 = 3-Tensor(cube)
n = n-tensor

#### Shape
Arrangement of data in the tensor

[[1,2,3],[6,8,9]] => Shape is [2,3] 
[1,3,1,4] => Shape is 4

##### Data types
float32/64... etc

Quantitized values are scaled to fit into smaller representations. Helps perf greatly at times.

#### 







