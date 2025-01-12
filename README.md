# MNIST Digit Classification with CNN in PyTorch

This repository demonstrates the implementation of a Convolutional Neural Network (CNN) using PyTorch for classifying handwritten digits from the MNIST dataset. The project covers the entire workflow, from data preprocessing to training, evaluation, and external image predictions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the environment, ensure you have Python installed and run the following command to install the required libraries:

```bash
pip install torch torchvision matplotlib numpy pillow
```

## Usage

1. **Dataset Download**: The MNIST dataset is automatically downloaded when you run the script for the first time.

2. **Model Training**: Adjust hyperparameters like learning rate, batch size, and the number of epochs in the script, then train the CNN model on the MNIST training set.

3. **Model Evaluation**: Evaluate the trained model on the MNIST test set to display its accuracy.

4. **External Image Prediction**: Use the trained model to classify digits from custom images by setting the `image_path` variable to the file path of the image.

## Code Structure

- **Data Handling**: Loads and normalizes the MNIST dataset using `torchvision`.
- **Model Architecture**: Defines a CNN model with convolutional layers, pooling layers, and fully connected layers.
- **Training Pipeline**: Trains the model using Stochastic Gradient Descent (SGD) and evaluates its performance on the test set.
- **Prediction Utility**: Includes a function to classify digits from external images, complete with preprocessing steps.

## Results

- **Accuracy**: The model achieves a high accuracy of approximately 99% on the MNIST test dataset.
- **Visualization**: Displays prediction probabilities for each class, offering insights into the model’s confidence levels.

## Contributing

We welcome contributions to enhance this project. To contribute:

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git git commit -m "Add YourFeature"
   ```

4. Push your branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a Pull Request for review.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

---

