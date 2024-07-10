# SURGE-24
Automated Lung Morbidity from Non-Invasive Images (Chest X-ray images) using Convolutional Neural Networks

Introduction to the project:
Lung diseases are a significant global health concern, causing high morbidity and mortality (death). Early and accurate detection is crucial for effective treatment and improved patient outcomes. Chest X-rays are a non-invasive, readily available, and cost-effective imaging modality used for initial evaluation of lung abnormalities. However, interpreting chest X-rays can be challenging, requiring trained radiologists. This work explores the potential of Convolutional Neural Networks (CNNs) to automate the detection of lung morbidities from chest X-ray images. 

My work involved collecting a large dataset of chest X-ray images with annotations for various lung morbidities (e.g., Cardiomegaly, Atelectasis, Pneumonia, Pneumothorax & Fibrosis). Then, I employed data preprocessing techniques to standardize the images and improve model performance. I investigated the effectiveness of different CNN architectures, including a custom-designed CNN, pre-trained ResNet-18, ResNet-50 models and also implemented YOLOv5 and Detectron2 of Facebook AI Research (FAIR) on VinDr-CXR and NIH Chest X-Ray dataset containing more than 1 Lakh images for better bounding box detection. The models were trained and evaluated on the prepared dataset using standard metrics like accuracy, classification loss, Mean Average Precision(mAP) to assess their ability to detect lung abnormalities.

The results are expected to demonstrate the feasibility of using CNNs for automated lung morbidity detection from chest X-rays. This could potentially improve diagnostic accuracy, reduce inter-reader variability among radiologists, and expedite patient care. Additionally, the project will explore the limitations of CNNs and address considerations for real-world clinical implementation, such as interpretability and explainability of the models’ predictions. By advancing automated lung morbidity detection using CNNs, this work has the potential to contribute significantly to the fight against lung diseases, leading to earlier diagnosis and improved patient outcomes.  It also contributes to the body of knowledge in healthcare AI and provides a foundation for future innovations

