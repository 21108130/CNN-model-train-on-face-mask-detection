# CNN-model-train-on-face-mask-detection
# Face Mask Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to detect whether people are wearing face masks or not. The model is trained on a dataset of images with and without face masks.

## Getting Started

Follow these steps to set up and run the project.

### Prerequisites

- A Google account to use Google Colab
- Basic understanding of Python and machine learning

### Dataset

The dataset used for training the model consists of images with and without face masks. You can download the dataset from [here](https://example.com/dataset). Make sure the dataset is organized into two folders:
- `with_mask/`: images of people wearing masks
- `without_mask/`: images of people without masks

### Training the Model

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).
2. **Create a New Notebook**: Click on "File" > "New notebook".
3. **Upload the Dataset**: Upload the dataset to Google Colab. You can use Google Drive to make it easier to handle larger datasets.

```python
from google.colab import drive
drive.mount('/content/drive')
```

4. **Clone the Repository**: Clone this GitHub repository to your Google Colab notebook.

```python
!git clone https://github.com/your-username/face-mask-detection.git
```

5. **Navigate to the Project Directory**:

```python
%cd face-mask-detection
```

6. **Install Dependencies**: Install the required Python packages.

```python
!pip install -r requirements.txt
```

7. **Train the Model**: Run the training script to train the model.

```python
!python train.py
```

### Testing the Model

After training, you can test the model using new images to see how well it detects face masks.

```python
!python test.py --image_path path_to_your_image
```

### Results

The results will show whether the person in the image is wearing a mask or not.

## Files in the Repository

- `train.py`: Script to train the CNN model.
- `test.py`: Script to test the trained model on new images.
- `requirements.txt`: List of dependencies required to run the project.

## Contributing

If you want to contribute to this project, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the links and scripts according to your specific project details.
