# Semantic Vectors To Decode Brain Activation

### Description:
This project replicates a simplified version of the decoding model proposed by Pereira et al. (2018), focusing on determining the concepts subjects were exposed to using neuroimaging data. The dataset consists of brain activation levels (BOLD response) recorded at approximately 150,000 3D coordinates (voxels) for 180 concepts, each presented with corresponding pictures. 

### Objective:
The objective is to train a decoder using imaging data and semantic vectors to accurately decode semantic information from neuroimaging data. The decoding process is evaluated using an "average rank" metric through k-fold cross-validation.

### Results:

Firstly, we saw that of the 180 concepts, 134 were considered succesful, an impressive 74% of the set of concepts, with only 46 being classified as failed. Additionally, we saw from the top 15 succesful and failed concepts that are is a trend - the smaller and more common words were more likely to be successful (do, food & time, for example, had the best (i.e. lowest) scores), whereas complicated and less commonly-used words (argumentatively & cockroach performed the worst) more often failed. We believe this outcome to be satisfactory.


