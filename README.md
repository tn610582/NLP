# Neural Machine Translation, English to Mandarin

In this project, we use Tensor-flow sequence-to-sequence(seq2seq) model to build a neural machine translation(NMT) tool to translate a sentence from English to Mandarin. The seq2seq model contains two Recurrent Neural Network (RNN), each for encoding and decoding. To improve the performance of the model, batching, padding and dropout techniques are used in the program. The training dataset is a translated TED presentation from IWSLT. The result shows that the overall translate accuracy is below 50%, because the limit size of the training data. However, we have found that shorter sentences has higher translate accu-
racy.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* You will need a python environment run the project.
* You can install Python for Mac and Windows from [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
* Or you can directly running it from [Google Colab](https://colab.research.google.com)

## Running the tests

* The project consists of three parts: data preprocessing, encoding and decoding.
* Also, please make sure you have tensor-flow installed in you python environment. 
* Tensor_flow installation can be found [here](https://www.tensorflow.org/install)

## Authors

* **Tianye Wang** - *Initial work* - [NMT_project](https://github.com/tn610582)
* **Zhiran WAng** - *Contributer* - 

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc






