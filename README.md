# Extraction-of-Pixels-of-Ducks-using-Bayes-Classifier
Bayes classifier to extract the pixels of duck bodies from the image
Bayes classifier to extract the pixels of duck bodies from the image
Manually collect as many sample pixels of duck body as possible from the given image
With the 3-dimensional ([red, green, blue]) feature vectors of duck-body pixels and non-duck-body pixels, building two Gaussian probabilistic likelihood models
From the two kind of pixels mean vector and covariance matrices can be estimated by the formula derived from the Maximum Likelihood Estimation
After deriving the two Gaussian distribution models apply the Bayes decision rule to classify every pixel on the given image
For visualization, output of an image which keeps every duck-body pixel classified with the use of classifier and replaces all non-duck-body pixels with black pixels
