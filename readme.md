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






