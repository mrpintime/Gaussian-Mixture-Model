# Gaussian-Mixture-Model
We use Gaussian Mixture Model (GMM) as a clustering algorithm to segmentate the pixels of a picture, and also we replace value of points of each segment with value of corresponded centroid.  

We can see how this model help us to reduce volume of a picture but still has enough information from original picture to recognize it.  
GMM is a Soft clustering algorithms can cluster data in partially one cluster and partially others.

# Description:  
Image segmentation is the process of segmenting an image into multiple important regions.  
We can use a GMM to segment an image into K regions (n_components = K) according to significant colors.  
Each pixel would be a data point with three features (r, g, b) (Or 1 feature if greyscale).
