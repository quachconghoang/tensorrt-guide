# tensorrt-guide

## PLAN A: Pytorch -> ONNX -> TensorRT
- Create a model with onnx support (YOLOv3)
- Using TensorRT to execute model
- Sample: https://github.com/nickmhnk/yolov3_onnx_tensorrt/blob/master/README.md
- Pytorch: load YOLOv3 weight - ONNX (?)
- Sample: https://jkjung-avt.github.io/tensorrt-yolov3/

## PLAN B: Pytorch: Torch Hub 
- Follow this instruction: https://pytorch.org/hub/nvidia_deeplearningexamples_ssd/
- Nvidia DL Examples for Tensor Cores: https://github.com/NVIDIA/DeepLearningExamples 

## PLAN C: Tensorflow -> UFF -> TensorRT (?)
- Use tensorflow to training model weights
- Convert model do UFF
- Convert UFF to TRT runtime


## Benchmark
- Jetson Nano: https://developer.nvidia.com/embedded/jetson-nano-dl-inference-benchmarks

