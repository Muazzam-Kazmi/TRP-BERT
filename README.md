# TRP-BERT
## Introduction
TRP (Transient Receptor Potential) channels are integral membrane proteins. The TRP superfamily of ion channels in mammals is made up of 28 cations permeable channels divided into seven subfamilies based on sequence similarity [1].These channel proteins are essential in sensory physiology including eye sight, sensing flavor and taste, touching, listing, smell, and heat and cold temperature. Many of these channels are triggered by a wide range of functions, processes, and stimuli [2]. TRP dysfunction causes numerous diseases in humans as well as they have a complex role in contributing and determining the progression of various disorders [3].

In the current study, we used representations from Bidirectional Encoder Representations from Transformers (BERT) [4] for identifying TRP channels from other channel proteins (non-TRP channels). BERT generates context-oriented word embedding by taking into account both the left and right sides of a given word in a phrase. The left and right direction learning ability of BERT makes it unique from the existing context-free embedding techniques that only generates embedding by looking at the left or right direction in a sentence. BERT brought revolution in the Natural Language Processing field by obtaining the latest results of eleven NLP tasks. Therefore, we used various pre-trained BERT models as a new feature extraction technique to extract features from protein sequences.

## Our Contributions
We have also listed our contriubtions as follows:

For the present study, we have contructed a new dataset about TRP channels.
We are the first research group to apply a powerful and advanced machine learning approach to classify TRP channels from non-TRP channels.
Importantly, we devised a new approach to generate representations for complete sequence from pre-trained BERT models, and eliminated the constrain on the length of the input defined by the BERT.

## Methodology
Using pre-trained contextual embeddings obtained from entire protein sequences, we devised a method for classifying TRP channel proteins from other channel proteins (non-TRP channels). We used BERT to represent all the protein sequences in our dataset. We provided the contextual representations obtained from the protein sequences by using pre-trained BERT models to a popular classification approach called Support Vector Machine (SVM). The SVM then discriminates whether a given protein sequence belongs to TRP channels or not based on the learning from contextualized representations.

## References
1. Samanta, A., Hughes, T. E., & Moiseenkova-Bell, V. Y. (2018). Transient receptor potential (TRP) channels. Membrane Protein Complexes: Structure and Function, 141-165.
1. Venkatachalam, K., & Montell, C. (2007). TRP channels. Annu. Rev. Biochem., 76, 387-417.
1. Nilius, B. (2007). TRP channels in disease. Biochimica et Biophysica Acta (BBA)-Molecular Basis of Disease, 1772(8), 805-812.
1. Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.
