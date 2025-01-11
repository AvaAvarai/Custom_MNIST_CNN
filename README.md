# Custom_MNIST_CNN

Custom Convolutional Neural Network (CNN) for experimentation with on the MNIST dataset for open character recognition. Experimenting with architecture and visualization of the model's kernel and weights. Current architecture is a single convolutional layer followed by Leaky ReLU activation, max pooling, and a fully connected layer with softmax output, trained using an Adam optimizer with He initialization.

Best results so far with an 80:20 train:test split over 10 epochs is 92% accuracy.

## Requirements

Python 3.8+, recommended Python 3.10+.

Python packages:

- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

To install the pip requirements, run the following command:

```bash
pip install -r requirements.txt
```

We recommend using a virtual environment to manage dependencies.

## License

This project is freely available, for both personal and commercial use, under the MIT license, see the [LICENSE](LICENSE) file for details.
