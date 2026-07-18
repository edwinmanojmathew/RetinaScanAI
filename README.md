# RetinaScanAI
AI-powered diabetic retinopathy detection using ResNet50 and Grad-CAM explainability.
## Features

- Detects five stages of diabetic retinopathy
- ResNet50 deep learning model
- Grad-CAM explainability heatmaps
- Confidence score for each prediction
- Image upload interface in Google Colab
- Automatic download of pretrained model from Google Drive

## Classes

- No Diabetic Retinopathy
- Mild
- Moderate
- Severe
- Proliferative Diabetic Retinopathy

## Technologies Used

- Python
- PyTorch
- Torchvision
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Project Structure

```
RetinaScanAI/
│
├── RetinaScanAI.ipynb
├── README.md
├── sample_images/
└── .gitignore
```

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells.
3. The pretrained model is downloaded automatically.
4. Upload a retinal fundus image (or use one from the `sample_images` folder).
5. View the predicted class, confidence score, and Grad-CAM visualization.

## Sample Images

Example retinal images are included in the `sample_images` folder for quick testing.

## Future Improvements

- Web application deployment
- Larger training dataset
- Higher classification accuracy
- Real-time clinical screening support
