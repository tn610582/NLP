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

* The project consists of three parts: 
 	data preprocessing can be found in: data_preprocessing.ipynb
 	encoding and decoding can be found in: NMT_en_man.ipynb
* Also, please make sure you have tensor-flow installed in you python environment. 
* Tensor_flow installation can be found [Here](https://www.tensorflow.org/install)

## Authors

* **Tianye Wang** - *Initial work* - [NMT_project](https://github.com/tn610582)
* **Zhiran WAng** - *Contributer* - 

## Acknowledgments


* M. Collins [N-gram model](http://www.cs.columbia.edu/~mcollins/lm-spring2013.pdf)

* S. Sathasivam. [Logic Learning in Hopfield Networks]() 

* D. Jurafsky.  J. H. Martin. [Speech and Language Processing Ch3 N-Grams](https://web.stanford.edu/~jurafsky/slp3/3.pdf)

* P. Koehn, F. J. Och, D. Marcu. [Statistical Phrase-Based Translation.](https://aclanthology.info/pdf/N/N03/N03-1017.pdf)

* W. De Mulder, S. Bethard, M.-F. Moens. [A survey on the application of recurrent neural networks to statistical language modelling (2015) Computer Speech and Language,  30  (1) , pp. 61-98.]()

* D. Karani [Introduction to Word Embedding and Word2Vec.](https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa)

* [Seq2seq basics](https://google.github.io/seq2seq/)

* M. Schuster. Paliwal K K. [Bidirectional recurrent neural networks](https://www.semanticscholar.org/paper/Bidirectional-recurrent-neural-networks-Schuster-Paliwal/)






