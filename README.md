## Supervised Learning Final Project.

Goal is to see if we can classify samples if they have prostate cancer or not by their gene expression levels.  Data was obtained from the cancer genome atlas (TCGA.org).

Methods : A logistic regression was used as a supervised learning technique to assign if a sample was normal or tumor related to the training data obtained.

Results : The model performed with an accuracy of 94.5%, but did poorly with normal assignment with only 70% accuracy.

Final note : tumor files were split and uploaded to get under Github file size limit.  If you want to reproduce this you will have to unzip and concatenate all 4 files before running the jupyter notebook.
