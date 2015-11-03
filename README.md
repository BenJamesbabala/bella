# bella

Bblla is a software that makes labeling naural language datasets less painful.

### Motivation

Many tasks in Natural Language Processing (NLP) require labeled data. Examples include Sentiment Analysis, Text Categorization, Entity Linking and POS tagging. But creating and verifying such labeled data can be a painful process that is often done in Google Spreadsheets, raw CSV files or through external services such as Amazon Mechanical Turk. Typically the output of such a process is then transformed in some way before it can be fed into a Machine Learning system. If you want to re-label any of the data you may even need a full ETL pipeline.

Building a Machine Learning classifier typically resembles a [Build-Measure-Learn](http://steveblank.com/2015/05/06/build-measure-learn-throw-things-against-the-wall-and-see-if-they-work/) cycle. You build a classifier, measure its performance, learn about what kind of mistakes it makes, and then improve it. I found that most my time is spent measuring and learning, which involves collecting, inspecting, and labeling training and test data.

bella aims to make evaluation and labeling less painful by providing: 

1. graphical user inteface
2. database backend to manage labeled data

The GUI allows you to label and tag of data through convenient keyboard shortcuts and swipe gestures, visualize metrics and confusion matrices, and more. The database backend manages labeled data and exports it into various formats.

### Use Cases

- You have just collected a bunch of unlabeled data, by crawling a website for example, and need to label it. You could do this in a spreadsheet, but using bella is likely to be faster and more covenient.

- You are hiring people to perform data labeling. Instead of giving them instructions on how to work with spreadsheets and CSV files, you can point them to your bella project.

- You trained a classifier and need to evaluate its performance. By loading predictions and labels into bella you can easily visualize results (e.g. confusion matrices) and view classification metrics such as accuracy, recall and F1 scores.

### Example Usage

### Architecture

