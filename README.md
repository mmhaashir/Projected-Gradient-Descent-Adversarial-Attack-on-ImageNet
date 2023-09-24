# Projected Gradient Descent Adversarial Attack on ImageNet

## Introduction <a name="intro"></a>

This project demonstrates how to perform a Projected Gradient Descent Adversarial Attack on an image to misclassify it within the ImageNet dataset. We utilize TensorFlow, the Adversarial Robustness Toolbox (ART), and other Python libraries for this purpose.

![dav_image](https://pyimagesearch.com/wp-content/uploads/2020/10/basic_image_adversaries_header.png)

## Table of Contents

- [**Introduction**](#intro)
- [**Dependencies**](#dep)
- [**Installation**](#install)
- [**Usage**](#usage)
- [**Results**](#results)
- [**Contribution**](#contr)
- [**Conclusion**](#conc)

## Dependencies <a name="dep"></a>

To run this code, you will need the following Python libraries:

  - TensorFlow (as tf)
  - Adversarial Robustness Toolbox (ART)
  - Matplotlib (as matplotlib)
  - Requests
  - NumPy
  - PIL (Python Imaging Library)

## Installation <a name="install"></a>

1. Clone the repository:
   `git clone https://github.com/mmhaashir/Projected-Gradient-Descent-Adversarial-Attack-on-ImageNet.git`
   
3. Install the required dependencies:
   `pip install tensorflow adversarial-robustness-toolbox matplotlib requests numpy pillow`

## Usage <a name="usage"></a>

To run the Fast Gradient Adversarial Attack:

  1. Open the Jupyter Notebook or Python script provided in the project directory.

  2. Load the pre-trained ImageNet model using TensorFlow.

  3. Select an image of that you want to attack.

  4. Run the attack. The code will generate an adversarial image and display it alongwith the misclassified output.

  5. Optionally, you can save the adversarial image using PIL.

## Results <a name="results"></a>

After running the attack, you will observe that the image has been perturbed in a way that it gets misclassified by the pre-trained ImageNet model. The generated adversarial image will be displayed, and you can observe the misclassification.

## Contributing <a  name="contr"></a>

Contributions to this project are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.

## Conclusion <a name="conc"></a>

This project demonstrates the use of TensorFlow and the Adversarial Robustness Toolbox (ART) to perform a Projected Gradient Descent Adversarial Attack on an image, causing it to be misclassified by a pre-trained ImageNet model. Such attacks highlight the vulnerability of machine learning models to carefully crafted adversarial inputs.

Feel free to experiment with different parameters and images to gain a deeper understanding of adversarial attacks and their implications in machine learning security.
