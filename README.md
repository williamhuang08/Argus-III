# Argus-III

# Abstract
Bionic eyes, commonly referred to as retinal prostheses, provide a promising solution
to restore vision to the 200 million people who suffer from retinal degenerative diseases
worldwide. However, current FDA-approved implants are limited to low-resolution
grayscale images, making object identification and localization difficult for patients.
Furthermore, patients will face a steep learning curve to adapt to the prostheses.

To address these challenges, this study develops a novel methodology framework
that consists of three integral components: 1) an optimal transportation theory (OT)-
based virtual magnifier to localize and enlarge regions of interest (ROIs) while preserving
important features and curvatures; 2) a real-time image optimization framework
to encode the maximum amount of spatial and color information to patients through
attention mechanisms as well as color scheme comparisons; and 3) an autoencoder-OT
model to augment the optimized images.

Computational experiments through distortion maps showed that the magnifier enlarged
the ROIs with minimal area and angle distortion. Further, users were able
to select important features and optimize ROI densities according to their preference
through a “digital knob” user interface. In contrast to current schemes, the image optimization
framework demonstrated better visual quality, was computationally efficient
(less than 380 ms on tested cases), and allowed for optimal color mapping through
comparison studies. A prototype processing system confirmed the effectiveness of the
proposed optimization framework over current prostheses. Finally, the AE-OT model
augmented images from 6 datasets to generate an image library for patient training.

This research offers an accurate, scalable, and optimized architecture that will
enable the next generation epiretinal prosthesis.
