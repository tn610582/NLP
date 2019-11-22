# Neural Machine Translation, English to Mandarin

In this project, we use Tensor-flow sequence-to-sequence(seq2seq) model to build a neural machine translation(NMT) tool to translate a sentence from English to Mandarin. The seq2seq model contains two Recurrent Neural Network (RNN), each for encoding and decoding. To improve the performance of the model, batching, padding and dropout techniques are used in the program. The training dataset is a translated TED presentation from IWSLT. The result shows that the overall translate accuracy is below 50%, because the limit size of the training data. However, we have found that shorter sentences has higher translate accu-
racy.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need a python environment run the project.

You can install Python for Mac and Windows from [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

Or you can directly running it from [Google Colab](https://colab.research.google.com)

## Running the tests

The project consists of three parts: data preprocessing, encoding and decoding.
Also, please make sure you have tensor-flow installed in you python environment. 

Tensor_flow installation can be found [here](https://www.tensorflow.org/install)

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc






