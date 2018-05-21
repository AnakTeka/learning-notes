

# Just another repo of Python scripts and codes


Installing packages for python 3.6

```sh
python3.6 -m pip install <package-name>
```


## Scripts

- [Port Scan](scripts/portscan.py)
- [Brute force SSH logins using paramiko](scripts/ssh-dictionary-attack.py)
- [dynamic-firmware-analysis](https://github.com/secjey/dynamic-firmware-analysis)
- [Firmware Analysis Toolkit](https://github.com/attify/firmware-analysis-toolkit)
- [The most useful python snippets](https://github.com/progrmoiz/python-snippets)

## Algorithms

- [Sort Algorithms](pySorting/README.md)
- [All Algorithms implemented in Python](https://github.com/TheAlgorithms/Python)
- [Fourier Transforms](fourier-transforms/README.md)
- [find length of sequences of identical values in a numpy array (run length encoding)](run-length-encoding/run-length-encoding.md)
- [Smoothed z-score algo (very robust thresholding algorithm)](run-length-encoding/ThresholdingAlgo.py)
- [Noise Reduction](noise-reduction/README.md)


## Machine learning

- [split dataset](machine-learning/split_dataset.py)
- [Compute Receptive Field](machine-learning/computeReceptiveField.py)


Demo of thresholding algorithm

![Alt Text](run-length-encoding/ThresholdingAlgo.gif)

## word2vec

In this competition, the goal is to predict a sentiment label for a dataset of 50,000 IMDB movie reviews. The sentiment is binary so that IMDB ratings < 5 result in a sentiment score of 0 and ratings >= 7 have a sentiment score of 1. The XGboost algorithm was trained on a term-document matrix where each row is a tf-idf vector representation of a review.

<p align="center">
<img src="https://github.com/ifding/python/blob/master/word2vec/figures/word2vec_merged.png" />
</p>

The figure above shows a t-SNE embedding of the word vectors for the first 2000 reviews. The size of the word feature space was set to 5000. With a tree depth of 10 and 10 boosting iterations, XGboost algorithm achieves low test error rate.

References:  
*https://www.kaggle.com/c/word2vec-nlp-tutorial* 

## Speech Recognition

If you want to get to know some details about MFCC take a look at this great [tutorial](http://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html).

In classical, but still state-of-the-art systems, MFCC or similar features are taken as the input to the system instead of spectrograms.

However, in end-to-end (often neural-network based) systems, the most common input features are probably raw spectrograms, or mel power spectrograms. For example MFCC decorrelates features, but NNs deal with correlated features well. 

<p align="center">
<img src="https://github.com/ifding/python/blob/master/speech/figures/speech_features1.png" />
</p>

References:  
*https://www.kaggle.com/davids1992/speech-representation-and-data-exploration*

## Great plots

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)