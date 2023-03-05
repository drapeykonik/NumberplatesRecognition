# Numberplate Recognition #
This repository contains materials on the development of an algorithm for numberplates recognition. Detection neural networks (SSD and Faster R-CNN) and OCR neural networks are used for it. For each neural network dataset have been found, neural netwotks have been trained and tested.
## Files description ##
* Faster R-CNN. Training and Inference (IPython Notebook) - this notebook contains the process of format changing of dataset annotations to COCO format, training and inference of the Faster R-CNN neural network using MMDetection framework. Some results are provided too.
* SSD. Training and Inference (IPython Notebook) - same as with Faster R-CNN.
* OCR. Training and Inference (IPython Notebook) - contains the architecture of neural network, custom PyTorch dataset class, process of the training and inference of the network. Some results are provided too.
* Pipeline (IPython Notebook) - notebook with the result of working the entire recognition algorithm (Detection and OCR together)
* Results (IPython Notebook) - notebook with the results of training and inference. While each network was training, results was storing in JSON files. In this notebook these files are parsed and visualization of losses and metrics are provided.
> There are IPython Notebooks in this repository mostly. If GitHub render doesn't work, please, use [nbviewer](https://nbviewer.org/) to see notebooks.