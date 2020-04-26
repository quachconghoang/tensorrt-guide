# tensorrt-guide

## PLAN A: Pytorch -> ONNX -> TensorRT
- Create a model with onnx support (YOLOv3)
- Using TensorRT to execute model
- Sample: https://github.com/nickmhnk/yolov3_onnx_tensorrt/blob/master/README.md
- Pytorch: load weight -> ONNX -> TRT Engine 
- Sample: https://jkjung-avt.github.io/tensorrt-yolov3/

## PLAN B: Pytorch: Torch Hub 
- Follow this instruction: https://pytorch.org/hub/nvidia_deeplearningexamples_ssd/
- Nvidia DL Examples for Tensor Cores: https://github.com/NVIDIA/DeepLearningExamples 

## PLAN C: Tensorflow-1 -> UFF -> TensorRT (Deprecated from TRT 7)
- Use tensorflow to training model weights
- Convert model do UFF
- Convert UFF to TRT runtime
- TRT 7 Release note: https://docs.nvidia.com/deeplearning/sdk/tensorrt-archived/tensorrt-700/tensorrt-release-notes/tensorrt-7.html#rel_7-0-0


## Benchmark
- Jetson Nano: https://developer.nvidia.com/embedded/jetson-nano-dl-inference-benchmarks

