# Can we taste with our eyes? Decoding human taste anticipation within the amygdala
Christopher Song, Wenjia Chen, Qingwei Zhang


## Summary
This study analyzes an fMRI dataset in order to see if a model can be trained to differentiate human neural response patterns to visual food and non-food object stimuli.

This repository contains all scripts used to conduct pre-processing and analysis. A formal written report is available upon request.

"Can we taste with our eyes?" is our final group project for "Decoding the Brain: Multivariate Analysis in Cognitive Neuroscience", taught by Dr. Yuan Tao in Fall 2018. Submitted December 14, 2018.

 - [README.md](README.md)
 - [amygdala-mni-sym_3mm_mask.nii.gz](amygdala-mni-sym_3mm_mask.nii.gz) - fMRI data, pre-processed to match resolution of amygdala mask
 - [binary-amygdala-mni-sym_3mm_mask.nii.gz](binary-amygdala-mni-sym_3mm_mask.nii.gz) - fMRI data, with amygdala mask applied
 - [binary-mask-conversion-script.ipynb](binary-mask-conversion-script.ipynb) - script applying binary mask to fMRI data
 - [cwtwoe_script.ipynb](cwtwoe_script.ipynb) - script containing all analysis
 - [labels.txt](labels.txt) - food/non-food labels for fMRI images
 - [sub-01-anat-sub-01_T1w.nii.gz](sub-01-anat-sub-01_T1w.nii.gz) - original anatomical MRI scan

## References
Lalumiere R. T. (2014). Optogenetic dissection of amygdala functioning. *Frontiers in behavioral neuroscience*, 8, 107. 

O’Doherty, J. P., Deichmann, R., Critchley, H. D., Dolan, R. J. (2001). Neural Responses during Anticipation of a Primary Taste Reward. *Neuron*, 33(5): 815-826. 

Small, D. M., Veldhuizen, M. G., Felsted, J., Mak, Y. E., & McGlone, F. (2008). Separable substrates for anticipatory and consummatory food chemosensation. *Neuron*, 57(5), 786-97.

Smeets, P. A. M., Kroese, F. M., Evers, C., de Ridder, D. T. D. (2013). Allured or Alarmed: Counteractive Control Responses to Food Temptations in the Brain. *Behavioral Brain Research*, 248, 41-45.

Woods, E.A., Hernandez, A. E., Wagner, V. E., Beilock, S. L. (2014). Expert athletes activate somatosensory and motor planning regions of the brain when passively listening to familiar sports sounds. *Brain Cognition*, 87, 122-33.
