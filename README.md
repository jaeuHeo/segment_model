# segment_model

nvcr.io/nvidia/tensorrt:20.11-py3 docker 이미지 환경에서 구현하였습니다.

# tf2onnx 라이브러리를 사용하여 onnx 를 생성

python -m tf2onnx.convert --graphdef tensorflow-model-graphdef-file --output model.onnx --inputs input0:0,input1:0 --outputs output0:0

