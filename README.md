#  :brain:  Predicting the Blood-Brain Barrier Penetrability and LogBB of PET Tracers Using Neural Networks
**QBIO 465: Artificial Intelligence in Biology and Medicine Final Project**

**by Andrew Levy, Erika Li, and Tushar Zhade**

Predicting blood–brain barrier (BBB) permeability is critical for CNS drug and PET tracer development. We evaluated descriptor-based and graph-based neural networks for both binary BBB classification and logBB regression, using the B3DB dataset for training and a held-out PET tracer dataset for testing. While both models performed well in-domain (AUC ≈ 0.90), they failed to generalize to PET tracers, particularly misclassifying BBB− compounds. To understand this, we analyzed feature drift, structural dissimilarity, and embedding behavior, finding that the performance gap stems from domain mismatch rather than model limitations. Our results highlight the need for PET-specific data augmentation, domain adaptation, and biologically informed evaluation practices.
