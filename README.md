# MedAttnNet
# MedAttnNet: A Novel Architecture for Precise Brain Cancer Classification
# Introduction
Brain cancer is a serious problem causing a direct threat to human health, and efficient and early diagnosis is required for the improvement of the patient’s prognosis. Magnetic Resonance Imaging (MRI) has been demonstrated as a star non-invasive modality for neurological studies (such as cancers).
Recent progress in deep learning, specifically in convolutional and transformer-based architectures, has further advanced the ability
to classify medical images with high accuracy. In this paper, we introduce and evaluate a new hybrid model called MedAttNet,
which combines both CNN and attention mechanisms for brain cancer classification. MedAttNet is also compared with two stateof-the-art (SOTA) approaches, VGG19 and baseline CNN; the former is a powerful visual feature extraction model based on deep CNN, and the latter is a new work focusing on hierarchical
attention for a better understanding of context. All three models were trained and validated on a publicly available T1-weighted contrast-enhanced brain cancer MRI database containing three types of cancers. Data augmentation was used to make the models more robust. Among the models compared, our proposed hybrid MedAttNet achieved the best classification accuracy, and the lowest computational complexity compared to those of VGG19 and the baseline CNN in general. The results suggest that our hybrid deep learning architecture can be very promising in the task of medical image classification, providing a robust, effective, and scalable approach to diagnosing brain cancers.

# Problem Statement
1. Brain cancer poses a critical threat to human health, requiring efficient and early diagnosis to improve patient prognosis and outcomes.
2. Traditional image processing methods rely on shallow feature extraction, which is insufficient for accurate medical image analysis and brain tumor classification.
3. Existing CNN-based models struggle with complex tumor differentiation, exhibiting higher misclassification rates between tumor subtypes (glioma, meningioma, and pituitary tumors)
4. Limited capability to capture both local and global features, as conventional architectures focus primarily on either local patterns or global context, but not both simultaneously

# Contribution
1. Development of a hybrid model combining the power of pre-trained ResNet-50 and CNN with a Transformer encoder for effective feature extraction and spatial attention, improving performance on medical image classification benchmarks.
2. Integration of modified Squeeze-and-Excitation (SE) blocks to recalibrate feature maps, refining channel-wise attention and promoting direct feature selection, which is critical for fine-grained classification. 
3. Introduction of a novel spatial attention mechanism within the Transformer encoder that models long-range spatial dependencies, while the pre-trained ResNet-50 backbone enables reduced training time, lower data requirements, and robust feature representations.
4. 
# Pipeline

![Workflow](https://github.com/proloy190902/MedAttnNet/blob/27be27ed30bcc322c14abb8c3d99181685bfd302/fig-1.png)


# Dataset: https://data.mendeley.com/datasets/mk56jw9rns/1
Rahman, Md Mizanur (2024), “Brain Cancer -  MRI dataset”, Mendeley Data, V1, doi: 10.17632/mk56jw9rns.1

# Dataset Description
Total Images: 6,056 T1-weighted contrast-enhanced MRI scans
Classes:
Brain Glioma: 2,004 images
Brain Meningioma: 1,717 images
Brain Tumor: 3,335 images

# Proposed MedAttnNet Architecture
![MedAttnNet](https://github.com/proloy190902/MedAttnNet/blob/23d5a3ab5626a37c112088440717b303037552ed/MedAttnNet.png)

# Architecture Components Details 
# Squeeze-and-Excitation Block
![SE](https://github.com/proloy190902/MedAttnNet/blob/5b1060986ea007eb9ffd990bc17da75c534afb2e/SE.png)

# Transformer Block
![Transformer]()
