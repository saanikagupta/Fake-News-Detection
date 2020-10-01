## Fake-News-Detection

### Prerequisites
- Keras 2.2.4
- Tensorflow 1.14.0
- NLTK 3.2.5
- Scikit-Learn 0.21.3
- Numpy 1.16.4
- Pandas 0.24.2

## Introduction:
"Fake News" is a term used to represent fabricated news or propaganda comprising
misinformation communicated through traditional media channels like print, and
television as well as non-traditional media channels like social media. The general
motive to spread such news is to mislead the readers, damage reputation of any entity,
or to gain from sensationalism.

![Screenshot](fakeNews.jpg)

### Code execution instructions
- Download the dataset and put it in same folder where Fake_News_Detection.ipynb is
placed. Or click on the [colab link](https://colab.research.google.com/drive/13yGZ9r4ja_cw2v1UDjN4nUkhy61jeEcI), open it in playground mode
and upload the downloaded files (train.xlsx, valid.xlsx and test.xlsx) in the colab.
- Run the IPython notebook section wise-
  - Import all the libraries.
  - Run the preprocessing section.
  - For six-way classification task-
    - Run 'Six-way classification section.
  - For binary classification' task-
    - Run 'Binary classification' section.


### Methodology
- I have implemented an Artificial Neural Network for both the classification tasks. 
- This shallow model outperformed other complex methods mentioned in reference papers.

**Please read the report for details.**

### Reference Papers
- William Yang Wang. [“Liar, Liar Pants on Fire”: A New Benchmark Dataset for Fake News Detection](https://arxiv.org/abs/1705.00648)
- Tariq Alhindi, Savvas Petridis, Smaranda Muresan. [Where is your Evidence: Improving Fact-checking by Justification
Modeling](http://www.cs.columbia.edu/~sdp2137/papers/evidence_paper.pdf)
