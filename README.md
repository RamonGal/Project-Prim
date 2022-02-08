# RECOGNITION OF ANTINUCLEAR ANTIBODY PATTERNS USING MACHINE LEARNING

## PROJET DE RECHERCHE ET D’INNOVATION MASTER (PRIM) - FINAL REPORT

Autoimmune diseases are an important field of medicine and sometimes it is necessary to identify
cellular patterns to correctly diagnose an illness. This project aims to create a network that classifies
specific antibody patterns for those kinds of diseases. 

Initially some types of image processing
techniques were applied, which in hand with a cellular segmentation package called Cellpose aimed
to automatically identify and segment every cell in a given image, using a U-net variant. Those
cells were pre-processed and given to a neural network to train with.  Multi-label and clusering methods 
were also studied for this problem for a more correct understanding of the cells.
With it, a path for inputting and
classifying external images was made.

This repository contains:
* The report explaining the work produced and its motivation.
* The code produced for this study:
  The code is ordered here using out image treatment pipeline, where the results from the previous work is used in the next.
  * Cellpose_nucleus_test
  * Segmented_nucleus_saved
  * Image_nucleus_study
  * Cellpose_cyto_test
  * Segmented_cyto_saved
  * Image_cyto_study
  * CNN_patterns
  * CNN_HEP
  * MultiLabel_CNN_HEP
  * Interimage_cell_clustering
   
  As well as :
  * Folder Guides - Guides on how anyone can make their own system by reusing ours
  * Folder Old notebooks - Notebooks that were exploratory and fundamental to the main notebooks above


* The dicts generated from them:
  They represent the avarage diameter of a cell within each class of antinuclear antibody pattern,
  for just the nucleus, as well as with the cytoplasm.
  * Avarage_Cyto.csv
  * Avarage_Nucleus.csv
  * Avarage_Pattern_Cyto.csv
  * Avarage_Pattern_Nucleus.csv
