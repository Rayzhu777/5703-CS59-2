# 5703-CS59-2
Federated Learning Model for Multimodal Disease Prediction from IU-CXR Dataset

This project explores the application of federated learning models in disease prediction.
 With the rapid development of the healthcare industry and the field of deep learning, the
 application of deep learning in the medical field has become more and more common.
 However, due to the rapid growth and diverse access to medical data, traditional medical
 diagnosis and prediction models are gradually unable to work effectively in the modern
 medical field. Due to the sensitivity and privacy of patient data, the traditional centralised
 approach to data sharing and model training has significant limitations in the medical field,
 and traditional models will not be able to perform at their total capacity if they do not have
 access to sufficient data. Therefore, developing a federated learning model with high accuracy
 and without sharing private patient data becomes essential.
 Currently, existing federated learning models face several challenges when used in health
care applications; for example, they tend not to be very effective when dealing with datasets
 combining medical images and diagnostic texts. In addition, traditional aggregation al
gorithms for federated learning models (e.g., Fedavg) are usually unable to effectively handle
 data differences between different clients, which results in unstable aggregation of the global
 model.
 To this end, this project proposes a novel multimodal model federated learning framework
 incorporating innovative dynamic aggregation algorithms based on weight changes for multi
category disease prediction. The fusion learning of medical images and clinical diagnosis
 text data is achieved by introducing ResNet-50 in the visual processing module and using a
 bidirectional LSTM model in the text processing module. Meanwhile, through the innovative
 dynamic weighted aggregation algorithm based on weight changes, the model can dynamically
 adjust the weights of the global model for the contribution of different clients, which improves
 the stability and accuracy of the model.
 This project aims to build a multimodal federated learning model with high accuracy
 while protecting patient data privacy. The specific research scope is the recognition of lung
 tumour diseases, focusing on the innovation of federated learning aggregation algorithms and
 the fusion learning of image-text data. Through the design and optimisation of the federated 
 learning framework, it is hoped that the accuracy of federated learning models in disease
 prediction and the prevalence of federated learning model applications in the medical field
 will be improved.
 Through experimental validation, the multimodal federated learning model proposed
 in this project exhibits excellent performance in the disease prediction task. Compared to
 the traditional Fedavg algorithm, the dynamic weighted aggregation algorithm significantly
 improves the accuracy of the global model in the multimodal data environment, and the
 convergence stability is also significantly improved. This demonstrates the effectiveness and
 stability of the model in multimodal healthcare prediction tasks.
 Although our model performs well in the experiments, the performance of the model is
 still limited by the quality and quantity of data, and further improvement in generalisability
 is needed. In addition, the computational complexity of the dynamic weighted aggregation
 algorithm may put too much pressure on clients with limited computational resources. In
 the future, we would like to continue to work on optimising the computational efficiency of
 the dynamic weighted aggregation algorithm and expand the usage scenarios of the model
 by adding more types of identified diseases to enhance the model’s flexibility and usefulness
 further.

