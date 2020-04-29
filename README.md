# EnsembleToponymInterlinking

This repository evaluates a series of approaches on top of the Toponym Interlinking task. It uses minimally adapted code from the [LinkGeoML/LGM-Interlinking](https://github.com/LinkGeoML/LGM-Interlinking) and [LuisPB7/StringMatching](https://github.com/LuisPB7/StringMatching) repositories. It consists of two sections:

1. A [BERT implementation](https://github.com/LinkGeoML/EnsembleToponymInterlinking/blob/master/1-BERT.ipynb) of the task based on the [Hugging Face Transformers](https://github.com/huggingface/transformers) library.
2. An evaluation of the three different approaches (BERT, LGM-Interlinking and StringMatching) as well as an ensemble scheme (via predictions averaging and stacking) of those ([here](https://github.com/LinkGeoML/EnsembleToponymInterlinking/blob/master/2-Ensemble.ipynb)).
