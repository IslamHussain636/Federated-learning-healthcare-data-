# Lightweight Models for APTOS 2019 Blindness Detection

This repository contains my work on training lightweight models like ShuffleNetV2, MobileNetV2, and ResNet to detect diabetic retinopathy using the APTOS 2019 Blindness Detection Dataset. The models are trained using federated learning, which allows for distributed training across multiple devices without sharing raw data.

## Introduction
Diabetic retinopathy is a serious eye condition that can lead to blindness if not detected early. This project aims to create efficient and accurate models for detecting this condition using lightweight neural networks. By using federated learning, we can train these models in a distributed manner, ensuring data privacy and security.

## Models
The following models are included in this project:
- **ShuffleNetV2**
- **MobileNetV2**
- **ResNet**

## Dataset
We use the APTOS 2019 Blindness Detection Dataset, which contains retinal images labeled with different stages of diabetic retinopathy.

## Requirements
To run this project, you need the following dependencies:
- `flwr[simulation]`
- `Ray` for memory management

Install them using pip:
```bash
pip install flwr[simulation] ray
```

## Installation
Clone this repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

## Usage
To train a model, use the following command:
```bash
python train.py --model <model_name>
```
Replace `<model_name>` with `shufflenetv2`, `mobilenetv2`, or `resnet`.

## Results
The results of the model training, including accuracy and other metrics, can be found in the `results` directory.

## Contributing
Feel free to contribute by opening an issue or submitting a pull request.



