# igm-selffocus-nn
A neural network for isotropic gyrotropic medium selffocusing inverce problem


**IGM_selffocus_nn.ipynb** contains main source code, divided on section according to the main computational steps

**.pth** files contain pretrained models, described in the paper, which you can upload in the last section of the notebook

*Elliptic.pth* Is the model, pretrained on the uniformly polarized light beam with Gaussian spatial distribution of amplitude.

*Singular.pth* Is the model, pretrained on the singular beam, comprised of Gaussian and Laguerre-Gaussian components.

*NoisyFalse.pth* Is the model, pretrained on the noisy singular beam with no input field channels.

*NoisyTrue.pth* Is the model, pretrained on the noisy singular beam with input field channels.

All these models are compatible with the Net only with default hidden_neurons parameter and activation functions!

**The datasets used in the study** are stored in kaggle and will be automatically downloaded in the notebook directory when you run the first section.

If something goes wrong with this method of uploading, you may manually download all the data from https://www.kaggle.com/unerriar/igmselffocus.

You may also manually train the model with the section "Training" and any hyperparameters you wish.

On any issues please contact unerriar@gmail.com
