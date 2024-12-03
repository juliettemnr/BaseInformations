==[[Speech BCIs]]== 

Detection and analyze speech : on a semantic level by differentiating different words or a signal level by detecting on and off speech.

**Overt speech** : 

*Classes* : 
- 5 words can be differentiated successfully : increasing voc
- other kind of classification : different lengths, distinction with semantic 
- audio EEG hybrid classification : different types of env noise 
- Usability of the system : see outside of the lab and use of ear EEG grade device (grand public)
- cross data set and cross user training

*Required data* :
- 80 samples per class : in 5 class classification in off but maybe more
- record EEG and audio : important for validation

*Interaction*:
- Standard training in front a screen 
Or focus on a work or daily task : simulate real world case

**Covert/Imagined speech**

*Classes* : 
- To do : Division in words and sentence 
- Offline : 
	- typically 4-5 words, but 9 words also exists
	- To make system usable : offline accuracy>90% for 4-5 classes
	- Full sentences could be interesting
- Online : 
	- from paper : 2 classes, from master thesis : ?
	- aim : 4-5 words

*Required data* :
- 80 to 150 samples per word

*Interaction*:
- Robot 
- what shall it look like : online with feedback ? offline only ?  screen bases ? VR-bases ? 


==[[Motor BCI]]===

**Motor intention**

*Required data*
- 3 experimental runs with a total of 40 movements for each type of movement 
- movement 'unilateral' and 'bilateral' : reaching movement with their arms to a target object

*Classes*
2 binary classification : 
- "no movement intention" (-) 
-  "movement  intention" (+)

*Interaction*
- Realistic scenario : person interacts with a exoskeleton
- natural speed arm movements : goal = griping a target object palced in front of them (bottle or cup)
- control resting phase of at least 5 seconds with feedback (usually visual)
- maybe auditory FB to more realistic FB 
- be careful with eye movement artefact : add fixation point 

**Motor imagery**

*Required data*
- at least 30-40 trials per class for ML algorithm
- 60-100 trials for online training with FB

*Classes*
2-3 classes (max 4) : 
- left-hand/right hand/both hands
-  foot, tongue MI

*Interaction*


