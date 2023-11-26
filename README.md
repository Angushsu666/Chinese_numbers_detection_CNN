# Chinese_numbers_detection_CNN

This project uses a Convolutional Neural Network (CNN) to recognize handwritten chinese digits. The model is trained on a dataset of handwritten chinese digits and tested on a separate dataset to evaluate its performance.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed:

- Python (version >= 3.6)
- Required Python libraries: numpy, PIL, keras, matplotlib

### Installing

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/handwriting-recognition.git
    ```

2. Navigate to the project directory:

    ```bash
    cd handwriting-recognition
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Data Preparation

Place your training images in the `train_image` folder and test images in the `test_image` folder. Ensure the images are grayscale and have a resolution of 28x28 pixels.

### Model Training

Run the following script to train the CNN model:

```bash
python train_model.py

Model Evaluation
Evaluate the trained model on the test dataset:

bash
Copy code
python evaluate_model.py
Results
The trained model achieves an accuracy of [insert accuracy here] on the test dataset.

Contributing
If you'd like to contribute to this project, please follow these guidelines.

Fork the project.
Create your feature branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Mention any contributors or resources that you found helpful.
Make sure to replace `[insert accuracy here]`, `your-username`, and other placeholders with the actual information. You can also include additional sections or details based on your project's complexity and requirements.
