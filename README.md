## Project Overview
This project focuses on classifying cotton plant diseases using deep learning.
Both a custom CNN and transfer learning models were explored.

## Models Implemented
- Custom CNN
- InceptionV3 (Transfer Learning)
- ResNet152V2 (Transfer Learning)

## Dataset
- ~2,000 images
- 4 classes: Healthy, Diseased (leaf & plant stages)
- Dataset not uploaded due to size

## Methodology
- Image preprocessing & augmentation
- CNN baseline model
- Transfer learning using pretrained ImageNet models
- Model comparison based on accuracy and efficiency

## Results
- InceptionV3 achieved the best performance
- Provided high accuracy with lower computational cost

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- Google Colab

## How to Run
1. Clone the repository
2. Install dependencies  
   `pip install -r requirements.txt`
3. Place dataset in `data/` folder
4. Run notebook from `notebooks/`

## Future Improvements
- Add real-time prediction interface
- Try lightweight models for deployment

