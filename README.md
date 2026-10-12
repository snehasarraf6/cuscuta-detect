# Cuscuta Infestation Classification

A web app that classifies plant images as **Cuscuta-infested** or **Healthy** using MobileNetV2.
The model runs entirely in the browser with ONNX Runtime Web, so no server is needed and images never leave the device.

- **Model**: MobileNetV2 with ImageNet transfer learning (exported to ONNX)
- **Dataset**: 940 original field photographs (470 per class)
- **Accuracy**: 100% on validation set
- **Built by**: Rahul Neupane & Kiran Prasad Neupane, SRM IST

## How to use
1. Upload a photograph of a plant (or use the camera)
2. Click **Analyse Plant**
3. Get the classification with confidence scores
