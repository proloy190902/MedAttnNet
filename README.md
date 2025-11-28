# MedAttnNet
# MedAttnNet: A Novel Architecture for Precise Brain Cancer Classification
# Introduction
Brain cancer is a serious problem causing a direct threat to human health, and efficient and early diagnosis is required for the improvement of the patient’s prognosis. Magnetic Resonance Imaging (MRI) has been demonstrated as a star non-invasive modality for neurological studies (such as cancers).
Recent progress in deep learning, specifically in convolutional and transformer-based architectures, has further advanced the ability
to classify medical images with high accuracy. In this paper, we introduce and evaluate a new hybrid model called MedAttNet,
which combines both CNN and attention mechanisms for brain cancer classification. MedAttNet is also compared with two stateof-the-art (SOTA) approaches, VGG19 and baseline CNN; the former is a powerful visual feature extraction model based on deep CNN, and the latter is a new work focusing on hierarchical
attention for a better understanding of context. All three models were trained and validated on a publicly available T1-weighted contrast-enhanced brain cancer MRI database containing three types of cancers. Data augmentation was used to make the models more robust. Among the models compared, our proposed hybrid MedAttNet achieved the best classification accuracy, and the lowest computational complexity compared to those of VGG19 and the baseline CNN in general. The results suggest that our hybrid deep learning architecture can be very promising in the task of medical image classification, providing a robust, effective, and scalable approach to diagnosing brain cancers.

# Pipeline

![Workflow](https://github.com/proloy190902/MedAttnNet/blob/27be27ed30bcc322c14abb8c3d99181685bfd302/fig-1.png)


# Dataset: https://data.mendeley.com/datasets/mk56jw9rns/1
Rahman, Md Mizanur (2024), “Brain Cancer -  MRI dataset”, Mendeley Data, V1, doi: 10.17632/mk56jw9rns.1
