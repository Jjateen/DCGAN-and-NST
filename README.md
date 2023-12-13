# DC GAN for Butterfly Generation

## Overview

This repository contains the implementation of a DCGAN (Deep Convolutional Generative Adversarial Network) for generating butterfly images. The model is trained on a dataset of butterfly images to generate realistic and diverse butterfly images.

## Dataset

The dataset used for training the DCGAN is a collection of butterfly images. You can find the dataset used for training in the `dataset` directory. Please make sure to provide proper attribution to the original sources of the dataset.

## Requirements

To run the code in this repository, you need the following dependencies:

- Python 3
- TensorFlow
- NumPy
- Matplotlib

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Training the DCGAN

To train the DCGAN on your own dataset, you can use the `train.py` script. You can customize the training parameters in the script, such as the number of epochs, batch size, and learning rate.

```bash
python train.py
```

## Generated Images

### 1st Epoch

![1st Epoch](images/epoch1.png)

### 25th Epoch

![25th Epoch](images/epoch25.png)

### 50th Epoch

![50th Epoch](images/epoch50.png)

## Results

The generated butterfly images show the progression of the DCGAN as it learns to generate more realistic and detailed images over epochs. The generator model improves its ability to create diverse and visually appealing butterfly images as training progresses.

Feel free to experiment with different hyperparameters, architectures, or datasets to achieve even better results.

## Acknowledgments

Special thanks to the contributors and sources of the butterfly dataset used in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
