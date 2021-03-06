# Object-Dectection with Transformers

Object Detection is a fundamental task in the domain of computer vision. Re-
cent advances in the vision transformer has led to many breakthroughs in tasks
such as image segmentation and classification. In our project, we want to extend
upon a dectection transformer, known as DETR, and address the issues it faces.
Our proposed methodology is to move away from the model’s reliance on convo-
lutional nuerual networks altogether and introduce a self supervised pre-training
methodology.

## Notebooks

1. BEIT-DETR-Train.ipynb – Training of our BEiT-DETR file. Look for changes in detr/models/detr.py
2. Inference-BEITDETR.ipynb – Inference using our BEiT-DETR trained weights
3. Plot_Model_Training_Logs.ipynb – Plot training logs
4. Removing_ResNet_Layer.ipynb – Project 2 Submission
5. BEiT_and_DETR_Understanding.ipynb – Reference Notebook that was used to understand the model architectures
6. Finetuning_DETR.ipynb – Refer to Pre-trained weights section

**Acknowledgement**: All code has been adapted from various sources. Most of the git clones will take you to the source from which the code has been adopted. 
