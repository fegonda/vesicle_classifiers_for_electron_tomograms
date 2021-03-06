# Automated classification of synaptic vesicles in electron tomograms of *C. elegans* using machine learning 
(https://doi.org/10.1371/journal.pone.0205348)

These tools can classify segmented neuronal vesicles as clear core- and dense core vesicles. 
They are optimized for *C. elegans* adult hermaphrodite and dauer larval vesicles in neuromuscular junctions that are segmented by [3D ART VeSElecT](https://doi.org/10.1371/journal.pcbi.1005317). However, they can be adapted to a wide range of data: The Python script trains several machine learning classifiers, for instance a linear support vector machine, on any four input features. The ImageJ macro subsequently applies trained support vector machine parameters to segmented vesicles.    

## Tutorials 
* please click [here](/How_to_use_the_python_script_KK_2_.pdf) for a PDF tutorial on how to adapt the Python script.
* and click [here](/How_to_use_the_classification_macro.pdf) for a PDF tutorial on on how to adapt the ImageJ macro.

## External Links 
For test images and additional information, please [follow this link](https://www.biozentrum.uni-wuerzburg.de/bioinfo/computing/3dart-veselect/).

## Further reading 
* [3D ART VeSElecT](https://doi.org/10.1371/journal.pcbi.1005317) 
* [Automated classification of synaptic vesicles in electron tomograms of *C. elegans* using machine learning](https://doi.org/10.1371/journal.pone.0205348)
