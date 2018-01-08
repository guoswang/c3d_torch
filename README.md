# c3d_torch
convert [c3d model](https://github.com/facebook/C3D/) from caffe to torch  
- The input color channel is already transformed from BGR (Caffe-style) to RGB for weights. The sports1m color mean npy file `sports1m-mean.npy` is converted from original `.binaryproto` file. See the test example in `extract_features.lua`. 
## download  
[c3d v1.0 torch model](https://www.dropbox.com/s/q878gj8bh8mick6/c3d_sports1m_it1900000.t7?dl=0)  
[c3d v1.1 torch model](#)  
