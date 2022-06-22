Brain-stroke-segmentation

This was my Bacherlor's dissertation project.

As the title says, using an MRI of an individual that has suffered a stroke as input, the developed CNN architecture had to be able to segment the tissue affected by the stroke. The developed model is based on the U-Net architecture.

The actual objective of the project was to evaluate the effect that the pre-processing had on the performance of the model. For this, a pre-processing pipeline consisting of: Skull-stripping, Bias field correction, etc, was developed. Finally, two models, one using the pre-processed data, and another using the raw MRI scan were evaluated.
