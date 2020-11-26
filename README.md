## About:
This repository contains the LaTeX sources for my master thesis. 
- Implementation portion available in [msc-neuro repository](https://github.com/petrroll/msc-neuro).
- For download as [.pdf here](https://github.com/petrroll/msc-thesis/raw/master/text/thesis.pdf) or online [through github](https://github.com/petrroll/msc-thesis/blob/master/text/thesis.pdf).

## Abstract:
Accurate models of visual system are key for understanding how our brains process visual information. In recent years, deep neural networks (DNN) have been rapidly gaining traction in this domain. However, only few studies attempted to incorporate known anatomical properties of visual system into standard DNN architectures adapted from the general machine learning field, to improve their interpretability and performance on visual data.

In this thesis, we optimize a recent biologically inspired deep learning architecture designed for analysis of population data recorded from mammalian primary visual cortex when presented with natural images as stimuli. We reimplement this prior modeling in existing neuroscience focused deep learning framework NDN3 and assess it in terms of stability and sensitivity to hyperparameters and architecture fine-tuning. We proceed to extend the model with components of various DNN models, analysing novel combinations and techniques from classical computer vision deep learning, comparing their effectiveness against the bio-inspired components. 

We were able to identify modifications that greatly increase the stability of the model while securing moderate improvement in overall performance. Furthermore, we document the importance of small hyperparameters adjustments versus architectural advantages that could facilitate further experiments with the examined architectures. All-new model components were contributed to the open-source NDN3 package. 

Overall, this work grounds previous bio-inspired DNN architectures in the modern NDN3 environment, identifying optimal hyper-parametrization of the model, and thus paving path towards future development of these bio-inspired architectures.

## Prerequisites:
- LaTeX (`texlive-full` or equivalent)

## Building:
- Makefile located [in](https://github.com/petrroll/msc-thesis/blob/master/text/Makefile) `text/Makefile`

## Template:
Slightly reorganized official MFF CUNI template for typesetting master thesis by Martin Mareš. More information in the [template readme](https://github.com/petrroll/msc-thesis/blob/master/README_template) or on the the [official website (cz only)](http://mj.ucw.cz/vyuka/bc/pdfaq.html).
