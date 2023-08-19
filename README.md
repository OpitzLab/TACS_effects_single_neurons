# TACS_effects_single_neurons



These folders contain the data set for of 25 neocortical cells with various dynamics (each folder is independent of each other). Here, we investigated the effects of tACS amplitudes on computational models of single neocortical neurons. 

## Information about the neocortical cells used
Models in this study are based on the human models in https://senselab.med.yale.edu/modeldb/ShowModel?model=241165.

## Software requirements and instructions
The data were generated using NEURON environement 7.8.1.  You can download this software here https://neuron.yale.edu/neuron/. 
Assuming NEURON has been installed, the MOD files in the 'mechanisms/' folder need to be compiled using mknrndll. Copy then nrnmech.dll from 'mechanisms/' up one level to the main folder.
In the main file "init.hoc", do not forget to modify the path of the working directory.

## Reference
Please use the following reference: 
Tran, H., Shirinpour, S., & Opitz, A. (2022). Effects of transcranial alternating current stimulation on spiking activity in computational models of single neocortical neurons. Neuroimage, 250, 118953.

## License
The code is licensed with the CC-BY-NC-SA license.

## Correspondence
htran - at- umn.edu (Harry Tran)

aopitz -at- umn.edu (Alex Opitz)
