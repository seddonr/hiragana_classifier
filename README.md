# Classifying handwritten Japanese characters (hiragana) using a neural net

## Information

* **explore.ipynb is the data exploration notebook**. It contains visual exploration of the data and walks through the data cleaning and engineering needed to make the data ready for classification. At the end of the notebook there is a short and simple train-test-split classification to verify that the data is ready for classification.

* **classify.ipynb is the classification notebook**. It contains clean and compact code that loads, cleans, engineers and classifies the data. Classification is done using k-fold cross-validation using a scikit-learn neural net, and the classifier performance is evaluated using learning curves and final accuracy scores.

* Dataset: 平仮名73文字版 (Hiragana 73 Character Edition dataset) from the Research and Development for Next-Generation Systems Office, National Diet Library: https://lab.ndl.go.jp/cms/hiragana73