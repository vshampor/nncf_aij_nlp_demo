This folder stores a simple semantic segmentation Pytorch training pipeline for UNet on CamVid with pre-trained weights and a Jupyter notebook that demonstrates the process of integrating the NNCF (https://github.com/openvinotoolkit/nncf) into the existing training code with purpose of obtaining a quantized model using quantization-aware training, as an alternative to the post-training quantization.

## Usage
### Prerequisites
To run this demo, a machine with at least one NVIDIA GPU on board is required.

### Use Docker
A Dockerfile is enclosed with this repository which will produce a Docker image with required dependencies installed and a Jupyter server automatically launcher.

Alternatively, you can:

### Run Jupyter notebook directly
Run the `transformers_with_nncf_int8_quantization.ipynb` notebook in this folder using your Jupyter environment.

The system prerequisites of both OpenVINO (https://github.com/openvinotoolkit/openvino) and NNCF (https://github.com/openvinotoolkit/nncf) must be installed.

