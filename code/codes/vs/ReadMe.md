Only support my caffe branch: https://github.com/happynear/caffe-windows/tree/ms . It contains a GPU bounding box regression layer,
a specified data transformer and a DLL with no Caffe headers(for fast compiling in other programs). 

It is approximately 2~3 faster than the original Matlab version. I am still attempting to refactor the first network by multi-thread inference. It's really a difficult work. If you have any suggestions, please contact me via the Issue in my caffe-windows
repository https://github.com/happynear/caffe-windows/issues/168 .
