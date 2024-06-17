Bioinformatics Summer School: Improving AI-based bioimage analysis
==================================================================

Artificial Intelligence (AI) algorithms outperform classical image analysis methods, however, the performance of these models is highly dependent on the quality of the annotated image datasets used to train them. In this project, you will explore the application of AI for biological imaging and the relationship between model training data and model performance. You will use models stored in the BioImage Model Zoo and data in the BioImage Archive to fine-tune and aggregate AI outputs. The aim of this project will be to test, evaluate, and improve model performance on a diverse set of microscopy images and annotations within the BioImage Archive. You will learn how to apply, train, tune, and employ the most performant state-of-the-art computer vision models. This project serves as a valuable demonstration of how FAIR (Findable, Accessible, Interoperable, Reusable) data plays an essential role in the training and enhancement of AI models.

Scenario
--------

There are a few different scenarios - you will discuss these at the start of the group project time in the course.

Scenario 1:

You are interested in a biological question/research project and you have the necessary microscopy data. For the project, you need to segment the nuclei and/or cytoplasm using AI. However, you tried an off-the-shelf AI model and it didn't segment most of the cells or gave inconsistent results. You want to improve these results or better train a model to give the best performance for your dataset. However, you don't have ground truth segmentations for your dataset and you don't have the expertise to provide some or you don't want to spend many hours doing that. You choose one of the datasets in the BioImage Archive that is similar to yours and that has ground truth segmentations. You will use this dataset to train different models to give the best performance for your dataset.

Scenario 2:

You are interested in a biological question and decided you can use a dataset that is in the BioImage Archive to investigate if that's possible. To do this you need to segment the nuclei and/or cytoplasm using AI. You first try an off-the-shelf AI model but it doesn't segment most of the cells or gives inconsistent results. You want to improve these results or better train different models and choose the one with the best performance for your dataset.

Scenario 3:

You have or want to write your own ML model for segmentation and you want to compare its performance with other models but you don't have any ground truth data. You choose one of the datasets in the BioImage Archive with ground truth segmentations. You will use this dataset to train different models including your own model and compare the results to evaluate. When you are happy with your model's performance you will share it with the world by uploading it to the BioImage Model Zoo and/or Hugging face.


Dataset
-------

-   Nuclei +/- Cytoplasm

-   2D dataset

-   Minimum 50 images

-   Ground truth annotations

-   AI galleries 

-   Accessible in the API

1.  An annotated fluorescence image dataset for training nuclear segmentation methods: <https://www.ebi.ac.uk/biostudies/BioImages/studies/S-BIAD634>

And AI Gallery view:

<https://www.ebi.ac.uk/bioimage-archive/galleries/S-BIAD634-ai.html>

1.  Confocal microscopy images of human cells: <https://www.ebi.ac.uk/biostudies/BioImages/studies/S-BIAD144>

And segmentation masks for S-BIAD144: <https://www.ebi.ac.uk/biostudies/BioImages/studies/S-BIAD916>

1.  Confocal microscopy and smFISH data of arabidopsis thaliana root cells: <https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD425>

And segmentation masks for S-BIAD425:

<https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD962>

1.  ZeroCostDL4Mic Stardist example training and test dataset: <https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD895>

2.  3D cell shape of Drosophila Wing Disc: <https://www.ebi.ac.uk/bioimage-archive/galleries/S-BIAD843-ai.html>

3.  Spinning disk confocal microscopy images and segmentation masks of African green monkey kidney cell line cells transfected to express SARS-CoV-2 antigens: <https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD1076>

4.  Non-nuclear segmentation: <https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD300>

Project aims
------------

Develop your project in the direction of your choice, identifying interesting biological questions and models to test. Do not worry if you do not complete all the suggested aims.

-   Data ingest

-   Interact with BioImage Archive API

-   <https://github.com/BioImage-Archive/bia-explorer/tree/main/example_notebooks/api>

-   <https://colab.research.google.com/github/bioimage-archive/bia-training/blob/main/notebooks/Simple_example_use_bia_explorer.ipynb>

-   API to Torchvision/torch tensors

-   <https://pytorch.org/tutorials/beginner/basics/data_tutorial.html>

-   <https://github.com/BioImage-Archive/pytorch_tutorial>

-   Data examples:

-   <https://pytorch.org/vision/stable/datasets.html#image-detection-or-segmentation>

-   Inference

-   BMZ

-   <https://github.com/bioimage-io/core-bioimage-io-python>

-   Cellpose 

-   <https://colab.research.google.com/github/bioimage-archive/bia-training/blob/main/notebooks/Working-with-public-image-data-as-OME-Zarr.ipyn>b

-   Metrics

-   IoU

-   <https://docs.monai.io/en/stable/metrics.html>

-   Model Training

-   Unet [monai]

-   Cellpose [<https://github.com/MouseLand/cellpose>]

-   BMZ

-   Model selection and comparison

-   Fine-tuned BMZ

-   End-to-end Monai 

-   Upload model to Zoos

-   Hugging face

-   BMZ
