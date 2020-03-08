# CTG-classifier

# Intro
A Cardiotocography (CTG) is a scan used by medical professionals to measure the foetal heartrate and mother's uterine contractions during pregnancy. CTG scans are performed to gain insight into the wellbeing of the unborn foetus.

In this project, an attempt is made to create a three class, neural network classifier to identify foetal status from a data set of diagnostic features. The status of the foetus is either N, S or P: Normal, Suspect or Pathologic. The dataset includes information from 2126 Cardiotocograms that measure foetal heartrate and uterine contractions. The dataset can be found at https://archive.ics.uci.edu/ml/datasets/cardiotocography.

# Hypothesis
A multilayer perceptron classifier's performance measured by sensitivity and precision on the 'NSP' class in the CTG dataset is affected by the activation function in the hidden layers.

- Null hypothesis H0 : Not enough evidence to support the hypothesis.

- Alternative hypothesis H1 : Evidence found indicating the hypothesis is true.

- The null hypothesis will be tested at the 5% significance level.

Tensorflow and Keras are used in a Jupyter notebook to create the neural network models along with numpy, pandas and scikit learn for array manipulation and visualisations.
