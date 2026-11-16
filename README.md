# Trust Thy Neighbours

Code for **"Trust Thy Neighbours: Probabilistic Pseudo-Labelling via Knowledge Distillation for Data-Scarce Wildlife Monitoring"** (NLDL 2027, PMLR vol. 352).

> 🚧 **Code coming soon.** The full pipeline, data splits and trained weights will be released here before the proceedings are published.

## Overview
A frozen DINOv2 teacher assigns soft pseudo-labels to unlabelled camera-trap images using distance-weighted votes from their $k$ nearest labelled neighbours. A ResNet50 student is then trained on both real-labelled and pseudo-labelled data, approaching fully supervised accuracy with a fraction of the labels.

## Data
Experiments use the Idaho and Missouri Camera Traps datasets from [LILA BC](https://lila.science). The exact splits, labels used and MegaDetector crop details will be provided as CSVs, since LILA may have had updates since our download.

## Citation
```bibtex
@inproceedings{laidlaw2027trust,
  title     = {Trust Thy Neighbours: Probabilistic Pseudo-Labelling via Knowledge Distillation for Data-Scarce Wildlife Monitoring},
  author = {Laidlaw, Rachael Joanne and Morris, Dan and Beery, Sara and Wray, Michael},
  booktitle = {Proceedings of the Northern Lights Deep Learning Conference (NLDL)},
  series    = {Proceedings of Machine Learning Research},
  volume    = {352},
  year      = {2027}
}
```

## Licence
Code: MIT (see `LICENSE`). Data splits derived from LILA BC datasets follow their original licence (CDLA-Permissive 1.0).
