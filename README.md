# Brain-Computer Interface Movement Decoding
This repository has the source code for an ML project that uses electroencephalogram (EEG) signals to determine whether a user wants to choose the left or right choice. The accompanying PDF file, Brain-Computer-Interface-Movement-Decoding.pdf, has extensive information on the modeling technique, outcomes, etc.

## Modeling Approach
From the subject's EEG data, we trained a support vector machine to distinguish between left and right planned movements. To deal with the dataset's high dimensionality, an SVM was used. The accompanying PDF details the several enhancements made to a simple SVM.

## Dataset
I utilized two separate datasets to assess the modeling strategy. There is a dataset we dubbed "overt" that includes information from people who were actively using their left or right hands to choose an item. We referred to the second group of data as "imagined" since it includes instances when people are only visualizing moving their left or right hand, rather than really doing so.

## Code
Due to Duke University's confidentiality requirements, I cannot display the code in the public code repository.
