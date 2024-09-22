# Bird Species Classifier

## Project Overview:
This project aims to develop a multi-class classifier that can accurately identify 200 different bird species from images. Using EfficientNet-B7 as the backbone model, I implemented transfer learning to classify each image with a corresponding confidence score. The project was completed using Colab GPU resources for efficient training.

## Key Features:
- Dataset: 200 bird species images with bounding box coordinates (not utilized in this model).
- Model: Pre-trained EfficientNet-B7 for transfer learning.
- Accuracy: Achieved 69.23% accuracy on the test dataset.
- Predictions: Output includes predicted label and confidence score.

## Dataset:
The dataset contains images of birds, each representing one of 200 species.
Test dataset provided in `test.csv` format with the following columns:
- path: The file path of the image.
- predicted_label: The bird species predicted by the model.
- confidence_score: Confidence of the model in the prediction.

## How to Run the Model:
1. Clone the repository:

   ```
   git clone https://github.com/your-repo/bird-classification
   ```
2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```
3. Train the model:
- Use Colab for optimal training with GPU support.
- Adjust batch sizes and epochs as needed in the code.
- Utilize the provided bird species dataset.
  
4. Make predictions:
- Use the trained model to predict bird species on the test dataset.
- Save the results in predictions.csv with the following headers
  
5. Results
- Accuracy: 69.23% using EfficientNet-B7.
- Innovation: Explored pre-trained architectures and transfer learning to improve classification performance.

6. Future Improvements
- Implement advanced data augmentation techniques to improve generalization.
- Experiment with utilizing bounding box coordinates for finer localization.
- Optimize the model for higher per-class accuracy and better overall performance.
