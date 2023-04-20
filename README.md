# Liver Cancer Segmentation 🩺🖥️
Training of semantic segmentation models to recognize the presence of liver and liver cancer in abdominal CT scans. 🚀 

This repository contains several Jupyter Notebooks that demonstrate the process of fine-tuning SegFormer and BEiT models over a liver tumor dataset. There are also notebooks that deal with data processing and preparation as well as model testing and result evaluation. In addition, a PDF document thoroughly describes the project.

## Project Description 📝

Liver tumor segmentation is an important task in medical image analysis. In this project, we fine-tune two state-of-the-art semantic image segmentation models, SegFormer and BEiT, over a liver tumor dataset. The dataset consists of CT images of liver tumors and corresponding segmentation masks. We preprocess the data to generate image-label pairs and augment the data to improve model generalization. We then fine-tune the models using transfer learning and evaluate the results using various metrics. The PDF document provides a detailed overview of the project, including the methodology, results, and conclusion.

## Dependencies 🛠️

- Python 3.8+
- Transformers 4.27.4
- Datasets 2.11.0
- Evaluate 0.4.0 
- huggingface-hub 0.13.4 
- PyTorch 1.13.1+cu116
- TorchVision 0.10+
- OpenCV 4.5+
- NumPy 1.21+
- Matplotlib 3.4+
- Pandas 2.0.0+
- tqdm 4.62+
