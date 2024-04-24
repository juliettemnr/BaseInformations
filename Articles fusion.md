
*Frikha et Moalla, 2015 : 
=> test possibility to use a AHP to determine weight of sensors withe BFT 


*Zhu et al 2022*

Dempster Shafer Evidence theory : decision level-fusion 


*Cheng et al 2020*

Data fusion of EEG and Eye movement for motion imagery BCI 

Data preprocessing and feature extraction

EEG => ICA

five eye movement features for MI classification: 
- **pupil diameter
- **fixation coordinates** (including abscissa and ordinate): a simple way to model the coordinates of fixation is to calculate the centroid over all samples within the position profile
- **saccade length** : sum of the lengths of all saccades on the current AOI, including both regression (i.e., back tracking) and skimming saccades (i.e., forward tracking) that can help a reader achieve a better understanding of the information
- **fixation duration** : total time duration of a AOI.
- **fixation count**: total number of fixations in each area of interest (AOI) of a certain period of time

=> to which feature is the most relevant : SVM : classification accuracy 
P.6 : explication stats pour choisir feature de l'ET : peut être intéressant pour nous 

==Feature layer ==

two commonly method : template upgrading and heterogeneous feature fusion 
=> it is impossible and invaluable to fuse them on the data layer, so we decided to utilize a heterogeneous feature fusion method to realize data fusion on the feature layer

**heterogeneous feature fusion** : combines eigenvectors from different information sources

normalize feature before fusion : mini-max method : normalization EEG and eye movement 
CNN classifier 

=> here binary classifier for MI task 

==Decision layer==

DS evidence theory 

two classifiers for EEG and ET 
=> then overall decision results 


- feature extraction was conducted on the collected EEG and eye movement data to obtain the corresponding eigenvectors
- the classifiers were used to classify these eigenvectors to produce preliminary results of each classifier
- D-S evidence theory was used for the final fusion

