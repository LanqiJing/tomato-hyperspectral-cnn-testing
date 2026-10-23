# Tomato Hyperspectral CNN Testing Package

This repository provides trained CNN model weights and testing materials for estimating SOD, CAT, and APX activities in tomato leaves under salt stress using visible-near-infrared hyperspectral reflectance.

## Supplementary Software S1

Download the model package:

[Supplementary_Software_S1_CNN_models.zip](./Supplementary_Software_S1_CNN_models.zip)

The package includes trained model checkpoints, preprocessing parameters, testing data, model definitions, and instructions for testing the models.

## Installation and Testing

1. Download and extract the ZIP package.
2. Install the required Python dependencies listed in `requirements.txt`.
3. Run the following command from the extracted package directory:

```bash
python test_models.py
```

See the included testing instructions for details.

## Citation

If you use these models or testing materials in your research, please acknowledge the original authors and cite the associated manuscript:

"Simultaneous Detection of Antioxidant Enzyme Activities in Tomato Leaves under Salt Stress Using Hyperspectral Imaging and Multitask Deep Learning."

The manuscript has been submitted to *Plant Phenomics* and has not yet been published. Full citation details will be added after publication.

See [CITATION.cff](./CITATION.cff) for citation metadata.

## Terms of Use

The trained model weights and associated testing materials are provided for academic research and verification purposes.

Users must acknowledge the original authors and cite the associated manuscript when using these materials in research publications.

Redistribution, modification, or repackaging of the trained model weights is not permitted without prior written permission from the authors.

Users must not present the models, code, or results as their own original work.
