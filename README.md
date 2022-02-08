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
* The code produced for this study:
  * Image

* The dicts generated from them:
  * Dict
