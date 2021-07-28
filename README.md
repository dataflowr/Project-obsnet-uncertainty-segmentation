# Triggering Failures: Out-Of-Distribution detection by learning from local adversarial attacks in Semantic Segmentation
Victor Besnier, Andrei Bursuc, David Picard & Alexandre Briot
International Conference on Computer Vision (ICCV) 2021
## Abstract
In this paper, we tackle the detection of out-of-distribution(OOD) objects in semantic segmentation. By analyzing the literature,
we found that current methods are either accurate or fast but not both which limits their usability in real world applications.
To get the best of both aspects, we propose to mitigate the common shortcomings by following four design principles: decoupling 
the OOD detection from the segmentation task, observing the entire segmentation network instead of just its output, generating 
training data for the OOD detector by leveraging blind spots in the segmentation network and focusing the generated data on 
localized regions in the image to simulate OOD objects. Our main contribution is a new OOD detection architecture called
ObsNet associated with a dedicated training scheme based on Local Adversarial Attacks (LAA). We validate the soundness of
our approach across numerous ablation studies. We also show it obtains top performances both in speed and accuracy when compared
to ten recent methods of the literature on three different datasets.

## Observer Architecture
![Alt text](img/teaser.png "Observer architecture")


## Code
Coming soon