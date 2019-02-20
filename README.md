# TensorRT3-errors-1
TensorRT3 cannot import name '_nv_infer_bindings'

You can check your path($ gedit ~/.bashrc) : export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:"tar_file_root/TensorRT-3.0.4/lib"

Then you should change your file name from 35 to 36 such as _nv_infer_bindings.cpython-35m-x86_64-linux-gnu.so to _nv_infer_bindings.cpython-36m-x86_64-linux-gnu.so.

Because my py is 3.6 and python in TensorRT3 release is 3.5. 

To change 35 to 36 in your anaconda paths:

(1):/home/zhu/anaconda3/lib/python3.6/site-packages/tensorrt/infer: _nv_infer_bindings.cpython-36m-x86_64-linux-gnu.so

(2):/home/zhu/anaconda3/lib/python3.6/site-packages/tensorrt/parsers/caffeparser: _nv_caffe_parser_bindings.cpython-36m-x86_64-linux-gnu.so

(3):/home/zhu/anaconda3/lib/python3.6/site-packages/tensorrt/parsers/uffparser: _nv_uff_parser_bindings.cpython-36m-x86_64-linux-gnu.so

(4):/home/zhu/anaconda3/lib/python3.6/site-packages/tensorrt/plugins:_nv_infer_plugin_bindings.cpython-36m-x86_64-linux-gnu.so

(5):/home/zhu/anaconda3/lib/python3.6/site-packages/tensorrt/utils : _nv_utils_bindings.cpython-36m-x86_64-linux-gnu.so

