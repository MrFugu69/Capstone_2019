# Capstone_2019
                                           CELLUAR IMAGE DENOISING & CLASSIFICATION 
                                           
`-------------------------------------------------------------------------------------------------------------`

**Dataset**: ~50GB of 6 channel Flourescent microscopy, [Kaggle](https://www.kaggle.com/c/recursion-cellular-image-classification) with 1,108 classes and 125,510 individual images from *Recursion Pharma*, the leader in Biological images [RxRx.a1](https://www.rxrx.ai/).  

**Background**:

Microscopy is an important skill for Biologists as well as the Medical community: for example viewing protein-protein interactions, cytoskeletal dynamics, as well as cellular ion concentrations <sup>[1](https://www.nature.com/articles/srep20640)</sup>. During processing images are often taken in low light or short exposure which cause inherent noise <sup>[2](https://ieeexplore.ieee.org/document/8327626)</sup>. 
Unfortunately, noise contributions during imaging create hurdles for interpretation as well as correctly identifying valuable assets within images. There are different kinds of noise but two common forms are (*Gaussian* white nose,*salt and pepper*). Filtering techniques are used to control noise such as (*median,non-local mean,bilateral,kernal density based local outlier factor, GridLof*) approaches. Often filtering will not be the only task at hand to resolve imperfections with image clarity or resolution which complicates matters. 

Imagine using clinical imaging such as microscopy to aid in drug deveolpment. The new age of bioinformatics will hedge on Machine Learning and Deep Learning. Currently, this is being brought to fruition through [Recursion Pharm](https://www.recursionpharma.com) and associated with [Kaggle](https://www.kaggle.com/competitions). The time frame to bring drugs to market averages around 10 years with a cost hundreds of millions of dollars according to Recursion Pharma. 

**Work Flow**: 

One of the challenges for advancing microscopy and Bioinformatics in terms of *AI*: (*Machine Learning or Deep Learning*) stems from the inability to sustain replicate images with identical characteristics. Here, I will attempt to form a process enabling [denoising] and clarification of images for future classification. This will be done with **Google Colab**, **Tensor Flow** and **Python 3**, all work will be done using Tensor Processing Units (*TPU*) which are far superior to *GPU* computation in parallel; due to computationally intensive work when using *Deep Learning* models.  
Remote storage buckets will be used with *Google Cloud* in order to store and access images. All dependencies will be supplemented through *Google Colab* and you will not need any external downloads. An example of denoising can be seen at [Meisam Rakhshanf Github](https://github.com/meisamrf/Image-denoising-tensorflow-keras)

**Goal**: Try to find a way to use *Machine Learning* to separate Biological variations and batch effects. A batch is a series of experiments executed together.Each batch introduces variation by either biological or tehnical variables. Finding a way to separate these would contribute greatly to the field of Biology and Drug Development. 

**Setup Resources**:

[colab tpu setup](https://colab.research.google.com/notebooks/tpu.ipynb) | [colab tpu help](https://medium.com/@jannik.zuern/using-a-tpu-in-google-colab-54257328d7da)

