
Tomato Hyperspectral CNN Testing Package

This repository provides trained CNN model weights and testing materials for estimating SOD, CAT, and APX activities in tomato leaves under salt stress using visible-near-infrared hyperspectral reflectance.

Supplementary Software S1

Download the model package:

[Supplementary_Software_S1_CNN_models.zip](./Supplementary_Software_S1_CNN_models.zip)

The package includes trained model checkpoints, preprocessing parameters, testing data, model definitions, and instructions for testing the models.

Installation and Testing

1. Download and extract the ZIP package.
2. Install the required Python dependencies listed in `requirements.txt`.
3. Run the following command from the extracted package directory:

```bash
python test_models.py
```

See the included testing instructions for details.

Citation

If you use these models or testing materials, please cite the associated manuscript:

"Simultaneous Detection of Antioxidant Enzyme Activities in Tomato Leaves under Salt Stress Using Hyperspectral Imaging and Multitask Deep Learning."

The manuscript is currently under review at *Plant Phenomics*. Full citation details will be added after publication.

See [CITATION.cff](./CITATION.cff) for citation metadata.
