

Ref intéressante pour preprocessing eye tracking : 
Julia Trabulsi, Kian Norouzi, Seidi Suurmets, Mike Storm, and Thomas Zoëga Ramsøy. 2021. Optimizing fxation flters for eye-tracking on small screens. Frontiers in neuroscience (2021), 1257. https://doi.org/10.3389/fnins.2021.578439


==*Cheng et al 2020*== 

five eye movement features for MI classification: 
- **pupil diameter
- **fixation coordinates** (including abscissa and ordinate): a simple way to model the coordinates of fixation is to calculate the centroid over all samples within the position profile
- **saccade length** : sum of the lengths of all saccades on the current AOI, including both regression (i.e., back tracking) and skimming saccades (i.e., forward tracking) that can help a reader achieve a better understanding of the information
- **fixation duration** : total time duration of a AOI.
- **fixation count**: total number of fixations in each area of interest (AOI) of a certain period of time

=> to which feature is the most relevant : SVM : classification accuracy 
P.6 : explication stats pour choisir feature de l'ET : peut être intéressant pour nous 
