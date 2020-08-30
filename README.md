# Depression-chatbot
An encoder-decoder architecture chatbot with an attention mechanism, designed to provide people wit a virtual companion. <br>The chatbot was trained on google collab using the depression data available on reddit.
## Project Pipeline
The project was divided into 5 stages.
* **Data Collection :**
The data for training the chatbot was collected from Reddit using the
name tags depression and psychiatry. The data was extracted using PRAW
(A python reddit API wrapper). A dataset of around 3750 sample points was built.
* **Data Cleaning :**
All the spelling mistakes, word contraptions, symbols were corrected and
removed. The dataset was cleaned for appropriate sample points.
* **Building Model Architecture**
The model was using encoder decoder architecture for Recurrent Neural
Network, along with Bahdanau attention mechanism for better model
performance via subclassing.
* **Model Training :**
Carried out on Google Colaboratory files. Model was trained only for 50 epochs, to provide a decent result, due to the computational expense.
* **Model Evaluation :**
Performance was kept track of recording the loss values at each epoch. <br>
Further attention analysis can also be carried out.
## References
* [Seq-2-Seq Models](https://nlp.stanford.edu/~johnhew/public/14-seq2seq.pdf)
* [NLP chatbot](https://towardsdatascience.com/deep-learning-for-nlp-creating-a-chatbotwith-keras-da5ca051e051)
* [Chatbot with Keras](https://medium.com/predict/creating-a-chatbot-from-scratch-using-kerasand-tensorflow-59e8fc76be79)
