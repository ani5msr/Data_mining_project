# Data_mining_project

## Data Mining and Classification for applications in Astronomy and Astrophysics

### The development of nanoelectronics industries has bought about a revolution in the
### field of Astronomical Instrumentation. This has seen the rise in the development of projects such
### as JWST, VLA, ALMA, which have ushered in a new era in observing extrasolar systems. The
### data, when converted to images, take the form of protoplanetary disks. These images have
### gaps in optical depths which may correspond to several features, but a primary one is the
### formation of new planets. The exact replication of these openings through simulations takes
### months of work to get results on a single image as data piles on. This calls for an automated
### network that could take data as images to predict properties such as the number of planets and
### their masses and locations. The advent of computer vision has made interpreting physical
### features possible in a model-consistent manner. This forms the basis for our choice of Bayesian
### Convolutional Neural Networks to be our model architecture. We will also use hyperparameter
### optimization to optimize our model. The purpose of this short course project is to form a short
### subtopic under the work done by Auddy et al. (2020,21) and Zhang et al. (2021). Both of these
### papers have considered work on multiplanet models as future work, so the current work of
### classifying between a single and multi-planet system would be a good precursor to further
### work*. The project’s novelty lies in the application, and working on tree pruning, and variable
### weights network provides an amalgamation of studies that have not been used much in such a
### physical problem. We also present a comparative against a normal CNN classifier. A problem
### for a network trained for this application is the lack of data to make a good supervised classifier.
### Working with hydrodynamic and radiative transfer simulations, we can make cases for various
### number of planets and use image augmentation to generate a dataset of ~15k simulated and
### observed images for the model to train on, thus working with well over 500 MB data limit as
### specified in the problem.
