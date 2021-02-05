# An application of Bayesian regression in visual neuroscience

## Intro 
In this project, I will demonstrate how to use Bayesian regression to analyze the relationship between two measured quantities, under the influenced of a third factor. The method is applied to a dataset in visual neuroscience, although the same process can be used on a wide range of scientific and clinical questions. This project is written in R and the JAGS package, and it is presented as a Jupyter notebook.

## The research question
In visual neuroscience, the the receptive field (RF) of a neuron is the region in the visual field where a stimulus can elicit it to respond. The size of the receptive field increases with its distance to the fovea. Characterizing this relationship is a fondamental problem in visual neuroscience.

In this project, I re-analyzed a dataset described in a paper that I co-authored ([Hadjidimitrakis et a. (2019)](https://www.jneurosci.org/content/39/27/5311.abstract) _Journal of Neuroscience_ 39, 5311-5325). In that paper, I came to the conclusion that this relationship is different in two different areas in the visual cortex. In this re-analyze, I will demonstrate that the inferential problem can be expressed in a more elegant and explicit way under the Bayesian framework. I will show that the Bayesian method provides a simpler explanation of the data, and highlight some of the pitfalls of the traditional approach to this problem, which relies on classical least-square methods.

 ## The dataset
 This analysis was performed under the consent of the owner of the dataset (Professor Marcello Rosa at Monash University). 
