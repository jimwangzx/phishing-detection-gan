# Phishing Detection GAN

## About

The primary objective of this project is to effectively model phishing website characteristics using Generative Adversarial Networks, and use it to detect phishing attacks. We use only the visual and textual characteristics of the phishing website to model the attacker's signature. The primary use-case of this idea would primarily be for situations which require expedited re-training of the neural network, which would otherwise take a significantly longer time, when using large amounts website metadata for formulating the signature. The extended re-training time required is a significant attack vector which could be exploited by malicious agents.

Please check the progress report <a href = "https://github.com/vignesh-pagadala/phishing-detection-gan/blob/main/docs/Progress-Report-Phishing-Detection-GAN.pdf">here</a> for detailed information, and goals achieved.

### Built With

* Python 3: https://www.python.org/download/releases/3.0/
* TensorFlow 2: https://www.tensorflow.org/ 
* PyTorch: https://pytorch.org/ 
* Jupyter Notebook: https://jupyter.org/

## Getting Started

### Prerequisites

* Python 3: https://www.python.org/download/releases/3.0/
* TensorFlow 2: https://www.tensorflow.org/
* PyTorch: https://pytorch.org/
* Anaconda distribution: https://www.anaconda.com/products/individual

### Installation

To install, clone the repo to your local machine:

`git clone https://github.com/vignesh-pagadala/phishing-detection-gan.git`

## Usage

To reproduce, run the code through the Jupyter Notebooks:

`cd docs/Notebooks/`

`jupyter-notebook DCGAN-Implementation-1.ipynb`

## Roadmap

See the [open issues](https://github.com/vignesh-pagadala/phishing-detection-gan/issues) for a list of proposed features (and known issues).

- [Top Feature Requests](https://github.com/vignesh-pagadala/phishing-detection-gan/issues?q=label%3Aenhancement+is%3Aopen+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Top Bugs](https://github.com/vignesh-pagadala/phishing-detection-gan/issues?q=is%3Aissue+is%3Aopen+label%3Abug+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Newest Bugs](https://github.com/vignesh-pagadala/phishing-detection-gan/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

## Support

Reach out to the maintainer at one of the following places:

- [GitHub issues](https://github.com/vignesh-pagadala/phishing-detection-gan/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+)
- The email which is located [in GitHub profile](https://github.com/vignesh-pagadala)

## Project assistance

If you want to say **thank you** or/and support active development of Phishing Detection GAN:

- Add a [GitHub Star](https://github.com/vignesh-pagadala/phishing-detection-gan) to the project.
- Tweet about the Phishing Detection GAN on your Twitter.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or personal blog.

Together, we can make Phishing Detection GAN **better**!

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.

We have set up a separate document containing our [contribution guidelines](docs/CONTRIBUTING.md).

Thank you for being involved!

## Authors & contributors

The original setup of this repository is by [Vignesh Pagadala](https://github.com/vignesh-pagadala).

For a full list of all authors and contributors, check [the contributor's page](https://github.com/vignesh-pagadala/phishing-detection-gan/contributors).

## Security

Phishing Detection GAN follows good practices of security, but 100% security can't be granted in software.
Phishing Detection GAN is provided **"as is"** without any **warranty**. Use at your own risk.

_For more info, please refer to the [security](docs/SECURITY.md)._

## License

This project is licensed under the **Apache Software License 2.0**.

See [LICENSE](LICENSE) for more information.