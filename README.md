# [Kaggle competition]HMS - Harmful Brain Activity Classification
Classify seizures and other patterns of harmful brain activity in critically ill patients

## Overview of the Kaggle Competition
This project is part of my participation in a Kaggle competition focused on a critical and transformative application of machine learning in healthcare. The competition's goal was to develop advanced models capable of detecting and classifying seizures and other harmful brain activities by analyzing electroencephalography (EEG) signals obtained from critically ill hospital patients.

The significance of this work lies in its potential to enhance the accuracy of EEG pattern classification drastically. Such advancements could revolutionize neurocritical care, epilepsy treatment, and drug development processes, enabling medical professionals and researchers to provide faster, more precise interventions.


# Competition Description
In medical practice, various tools, from the basic stethoscope to more complex technologies like EEG, are essential for patient care. EEG is particularly critical for monitoring critically ill patients to detect seizures and other brain activities indicative of potential brain damage. This competition aimed to automate the analysis of EEG signals, a task traditionally requiring manual inspection by specialized neurologists. Despite their expertise, manual analysis is time-consuming, costly, and susceptible to human error and inconsistencies.


By participating in this competition, I contributed to efforts aimed at automating EEG signal analysis. This automation is crucial for enabling quicker, more accurate diagnosis and treatment of seizures and related brain activity disorders. Additionally, the competition's outcomes could significantly aid drug development research targeting seizure prevention and treatment.

The competition categorized EEG patterns into six interest areas: seizure (SZ), generalized periodic discharges (GPD), lateralized periodic discharges (LPD), lateralized rhythmic delta activity (LRDA), generalized rhythmic delta activity (GRDA), and “other.” These patterns, annotated by expert consensus or identified through varying degrees of agreement, serve as the foundation for developing and evaluating the predictive models.

This is a example of the data used in this notebook 

![Example Image](ressources/exmaple_input.png)


## Project Contribution and Impact
Through my work in this competition, I engaged in creating a model using the Mix Transformer architecture that not only meets the technical challenge of classifying complex EEG data but also holds the promise of making a tangible difference in patient care and medical research. The Mix Transformer (MiT), as presented in "SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers"  Xieetal.,2021, served as the backbone of our approach. This choice was motivated by the architecture's efficiency and effectiveness in handling the spatial hierarchies inherent in EEG data.

The algorithms developed and insights gained have the potential to streamline EEG analysis, supporting medical professionals in their decision-making processes and aiding researchers dedicated to the fight against seizures and brain damage. By leveraging the advanced capabilities of the Mix Transformer, our model offers improved accuracy and reliability over traditional methods, thereby enhancing the diagnostic workflow and contributing to the broader research community's efforts to understand and treat neurological disorders more effectively.

## Reference:

Xie, E., Wang, W., Yu, Z., Anandkumar, A., Alvarez, J. M., & Luo, P. (2021). SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers. arXiv:2105.15203. https://arxiv.org/pdf/2105.15203.pdf

