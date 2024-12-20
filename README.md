## Can AI Predict Loan Success? A Comparative Study on Imbalanced and Noisy Greek Call Transcripts

This thesis deals with the challenging task of predicting loan arrangement success based on noisy Greek comments written by call center agents during communications with the customers. It is a comparative study of various machine and deep learning models and NLP techniques, employed to tackle an extremely imbalanced dataset (with the positive class accounting for only the 0.2\% of the total), and a high level of noise in the data, which stems both from abbreviations, syntactical and grammatical errors, and informalities, as well as from the weak supervision that has been used, since the labels were constructed based on business rules, instead of having been assigned by experts. The extensive exploration of different approaches ranges from traditional models like Logistic Regression and XGBoost, which are used in combination with feature extraction techniques such as term frequency - inverse document frequency (TF-IDF) and word embeddings, extending to more advanced language models capable of capturing deeper semantic meanings from the texts, like GreekBERT, Meltemi, and Llama 3.1 70B. Furthermore, different kinds of loss functions were utilized, the most notable being contrastive and class-weighted losses. The study was also severely constrained by limited computation resources besides the lack of positive examples, hence leading to experimentation with various optimization methods, like Low Rank adaptation (LoRA), quantization, gradient accumulation, learning rate decay, and weight decay. In order to mitigate the noise in the texts, both rule-based as well as AI-supported apprοaches were followed, including text refinement by a modern multilingual LLM. Regarding the uneven class distribution, synthetic data generation by a LLM was also put under investigation, to determine the efficacy and the impact this process could have in the performance evaluation. All these experiments were rigorously evaluated and compared using a comprehensive list of metrics, including classic ones like accuracy and recall, and also including metrics that are traditionally used for ranking models, like Recall@K, R-Precision and PR-AUC. The study concludes with discussion of the results and highlights the most effective strategies for handling the scarcity of positive instances and noise of data. Proposed future research directions include the development of more robust Greek language models, the exploration of advanced data refinement, augmentation and generation techniques, and the creation of publicly available datasets, in order to foster further advancements in Greek NLP and further democratize the access to novel AI tools.

### Datasets creation process
![alt text](https://github.com/iliacube/loan_arrangement_prediction_with_nlp/blob/main/Datasets%20creation.svg)

### ML experiments
![alt text](https://github.com/iliacube/loan_arrangement_prediction_with_nlp/blob/main/ML%20Models%20with%20NLP%20Techniques.svg)

### DL experiments with language models
![alt text](https://github.com/iliacube/loan_arrangement_prediction_with_nlp/blob/main/Deep%20Learning%20with%20Language%20Models.svg)
