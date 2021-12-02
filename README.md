# TACS_effects_single_neurons



These folders contain the data set for of 25 neocortical cells with various dynamics (each folder is independent of each other). Here, we investigated the effects of tACS amplitudes on computational models of single neocortical neurons. 

## Information about the neocortical cells used
A set of 25 neocortical cells was modified and used in this investigation and can be downloaded from ModelDB (click on this link https://senselab.med.yale.edu/ModelDB/default accession number: 066023 or directly click on this link https://senselab.med.yale.edu/modeldb/ShowModel?model=241165#tabs-1). 
This model already contains .hoc files necessary to run the model and additional and/or modified .hoc files can be found in the NEURON_code folder.
Further information about the cell dynamics can be found in [aberra2018biophysically].

## Software requirements and instructions
The data were generated using NEURON environement 7.8.1  You can download this software here https://neuron.yale.edu/neuron/. 
Assuming NEURON has been installed, the MOD files in the 'mechanisms/' folder need to be compiled using mknrndll. Copy then nrnmech.dll from 'mechanisms/' up one level to the main folder.

## Data analysis
NB: due to the large amount of data, the files for all neurons are not available on github. 
For the analysis of the data, a custom matlab code was used. 


## Reference
Please use the following reference: Tran et al. 2020. Effects of transcranial alternating current stimulation on spiking activity in computational models of single neocortical neurons. BioRxiv.

## License
The HOC code, Python code, synapse MOD code and cell morphology are licensed with the above mentioned CC-BY-NC-SA license.

## Correspondence
htran - at- umn.edu (Harry Tran)

aopitz -at- umn.edu (Alex Opitz)
