## Road Extraction :</br>

This repository contains code for the paper [Road extraction using K-Means clustering and morphological operations](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Road+extraction+using+K-Means+clustering+and+morphological+operations&btnG=).

# Road Extraction Using K-Means Clustering and Morphological Operations

The steps followed to obtained the road extracted image: 
 1) K-Means Clustering: The pixels are clustered according to their intensities. 

 2) Road Cluster Identification: Road clusters are identified from the cluters obtained. The cluster which has the longest component is choosen as the road cluster. 

 3) Road Cluster Filtering: Dilation and non-road area removal is performed. 

 4) Result Evaluation: The performance of the resultant image is evaluated by parameters like: completeness, correctness, and quality. 


### Pre-requisites

Before running the demo, make sure that the following python libraries are installed and working well. 

```
numpy
opencv-python
Matplotlib
wxPython
PIL
```

### Data

The sample images on which we ran our code and the corresponding output images can be found here.
These images are from the DeepGlobe challenge dataset.
