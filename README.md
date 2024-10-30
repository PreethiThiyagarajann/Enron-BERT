# Enron-BERT

 **Abstract**

 Digital (forensic) investigations will be increasingly important in both criminal
 investigations and civil litigations (e.g., corporate espionage, and intellectual
 property theft) as more of our communications take place over cyberspace (e.g.,
 email) and social media platforms. Our proposed model utilizes the topic
 modelling techniques such as BERTopic and LDA for extracting the topics from
 the content of communication messages.Feature selection is applied to rank the
 topics in order to find the most weighted topics associated with the target
 individual(s). With the ranked topics, the platform is trained with transformers
 known as BertForSequenceClassification, Convolutional Neural Networks with
 LSTM and Machine Learning model’s like Logistic Regression. The final
 outcome of integrating topic modelling techniques with deep learning models is
 compared with the outcomes of the machine learning classifiers using Normalised
 Mutual Information(NMI) as the evaluation metric.The output from the most
 effective classifier is then used to facilitate further investigation. The proposed
 system predicted criminals with accuracy of 97% for
 BERTforSequenceClassification, 92.24% for CNN and 92.51% for CNN
 incorporated with LSTM when compared to LDA’s Logistic Regression F1 score
 of 45% and 45.13% for Logistic Gradient Descent
