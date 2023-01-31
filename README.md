### Project Title: 
Sentiment Analysis of code-mixed Telugu-English text using Sequence Models

### Objective:
To develop a deep learning model for sentiment analysis of code-mixed data, where multiple languages are used in a single text.

### Data:
The project will use a publicly available Telugu-English code-mixed dataset, which will be preprocessed and cleaned. The data will be annotated with sentiment labels (positive, negative, neutral).

### Methodology:
A deep learning model such as a Convolutional Neural Network (CNN) or a Recurrent Neural Network (RNN) will be trained on the annotated data to identify the sentiment of the code-mixed text. The model will be evaluated based on its accuracy, precision, recall, and F1-score.

### Tools & Techniques: 
The project will be implemented using Python programming language and deep learning libraries such as TensorFlow. The model will be trained using a GPU for faster computation.
- Google Colab
- Python
- NLTK
- Tensorflow
- Gensim
- Scikit-Learn

### Significance: 
Sentiment analysis of code-mixed data is a challenging task due to the complexity of multiple languages in a single text. The deep learning model developed in this project will be useful for various real-world applications such as customer feedback analysis, social media analysis, and brand monitoring.

### Deliverables:
The project will deliver a trained deep learning model, a report on the experiment results, and the code used for training the model.

# Result
<table>
<thead>
<tr>
<th>Model</th>
<th>Accuracy</th>
<th>F1 Score</th>
</tr>
</thead>
<tbody>
<tr>
<td>Simple RNN</td>
<td>0.72</td>
<td>0.69</td>
</tr>
<tr>
<td>GRU</td>
<td>0.76</td>
<td>0.74</td>
</tr>
<tr>
<td>LSTM</td>
<td>0.75</td>
<td>0.74</td>
</tr>
<tr>
<td>Bi-LSTM</td>
<td>0.76</td>
<td>0.74</td>
</tr>
<tr>
<td>1D Convolution Network</td>
<td>0.76</td>
<td>0.75</td>
</tr>
</tbody>
</table>

Model: 1D ConvNet <br>

Confusion Matrix
![download](https://user-images.githubusercontent.com/73692009/215715024-b90d175e-918d-4dd5-b700-ecacea40b1c2.png)

Classification Report
![Screenshot 2023-01-31 143333](https://user-images.githubusercontent.com/73692009/215715837-93eabb40-b19d-4d81-8905-29c9a5ac183d.png)
