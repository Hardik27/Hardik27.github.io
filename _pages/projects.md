---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

**Hindi to English: Transformer-Based Neural Machine Translation** <br/>
_Feb 2020- Sep 2020_ <br/>
The project aims at translating texts from Hindi to English by training the Transformer model. For this, we first cleaned the IIT Bombay CLIFT English-Hindi parallel corpus and then applied word level and sub-word level tokenization for the vocabulary creation. We implemented back-translation to augment the training data by ~3.5 million parallel records. The Transformer model along with sub-word level tokenization and back-translation led us to achieve state-of-the-art BLEU score on Hindi to English translation task. <br/>
[See Project](https://github.com/Hardik27/Hindi-to-English-Transformer-Based-NMT)

**Topic Modeling on Research Articles** <br/>
_Aug 2020_ <br/>
Developed a multi-class classifier that takes 'Title' and 'Abstract' as the input and predicts the category to which it belongs it. Pre-processed the data to remove noise characters and then implemented stemming and lemmatization. Trained and compared the results of BERT, RoBerta, OVR Logistic Regression, Binary Relevance models. Achieved a mircro F1 score of 0.837 on the test data of ~9,000 records. <br/>
[See Project](https://github.com/Hardik27/Topic-Modeling-for-Research-Articles)

**Dance form Identification using CNN and Transfer Learning** <br/>
_June 2020_ <br/>
Trained 364 images in the train set using 4 Pre-trained models viz: VGG16, VGG19, ResNet50 and InceptionV3. Using this Transfer-learning approach achieved an accuracy of 78.37% on the test set. To further increase the accuracy, implemented data augmentation technique to generate artificial images in the batches of 32. Data Augmentation along with Hyperparameter tuning finally led to an accuracy of 83.89% which placed me in top 2% in the pool of 5864 participants. <br/>
[See Project](https://github.com/Hardik27/Dance-form-Idenification)

**Employee Attrition Rate Prediction** <br/>
_June 2020_ <br/>
Implemented XGBRegressor and SGD Regressor for prediction the attrition rate if the employees using 22 input features. Applied different data pre-processing steps and achieved an accuracy of 81% on a test data of 3000 records. <br/>
[See Project](https://github.com/Hardik27/Employee-Attrition-Rate-Prediction)

**Malaria Detection using Transfer Learning and GAN** <br/>
_May 2020- June 2020_ <br/>
Fine-tuned InceptionV3, VGG16 and VGG19 models on the image data of the malaria-affected and unaffected cells. For this, I first pre-processed the dataset to resize into 48*48*3 resolution. Implemented DCGAN to augment the training data with the images of the cells that were infected with malaria. <br/>
[See Project](https://github.com/Hardik27/Malaria-Detection)
