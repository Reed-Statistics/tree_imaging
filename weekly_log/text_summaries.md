Text Summaries
----------------
  
### A Convolutional Neural Network Classifier Identifies Tree Species in Mixed-Conifer Forest from Hyperspectral Imagery
In this article, the authors apply a hyperspectral CNN model to analyze the pixels of hyperspectral imagery data and classify 7 different tree species. Their setup involved a single north to south strip of hyperspectral imagery data (16km long by 1km wide) taken over the mountains in California. The collected data from the remote-sensing imagery corresponds with a strip of land for which field data had been collected. The collected field data includes measured information about tree count, tree species, and mortality status. To build their models the authors separated the data into 10 folds and performed k-fold cross validation. The hyperspectral image was converted into the form of a tree canopy height model and circular polygons were centered at individual tree canopies in such a way that each circle was assigned a tree species and mortality status and treated as a single observation. A convolutional neural network was trained on the designated training data, and the results concluded that the model does a great job identifying pine trees at the genus level, and Jeffrey pine species, sugar pine species, and incense cedar species all had F-scores around 0.90 or more. One complication that came up was the uneven distribution of proportion of examples in each class, which the authors accounted for by applying a balanced loss function. Another model that the authors included in the article was an RGB model, which did not perform as well as the hyperspectral model in terms of distinguishing tree classes, but did perform similarly in terms of genus classification.
This article is relevant to my research because I will be conducting a similar project where I apply machine learning methods to satellite images to predict tree mortality.

### Land Use Classification in Remote Sensing Images by Convolutional Neural Networks
The authors begin with a discussion of the difficulties encountered when trying to classify land type through remote sensing. Many issues arise from the quality of the satellite images. For example, images composed by combining the images taken during multiple flight paths have a lot of variation due to the different times causing the sun’s angle to change and the weather conditions to vary. This article goes over the performance of convolutional neural networks in classifying land type when applied to different remote sensing images. Specifically, they are interested in exploring the performance of the GoogLeNet and CaffeNet models under trained data, as pre-trained nets, and with feature vector output on two remote sensing datasets. The results of the experiment conclude that using a pre-trained CNN is a successful approach to classifying land type.
This article is relevant to my research because it goes over the complications of classification based on remote sensing images, and how convolutional neural networks perform across images with different quality. It also is useful in helping me to understand how the outcomes of my machine learning models might vary depending on what images I will use.

### Western Redcedar Die Off in Seattle Parks, 
### Western Redcedar is Just One of Many BC Trees Facing Extinction,
### Western Redcedar Decline,
### Why is my Tree Dying? Western Redcedar (Thuja plicata)

These articles address a recent discovery that western redcedars in Canada, Washington, and Oregon are dying for reasons likely related to climate change. Currently, there is not a lot of professional literature reporting this decline, but many sources have comparable claims that western redcedars across the pacific northwest have noticeably declined. Specifically, over the past two years, these trees have thinner crowns, more fallen branches, sapwood wounds, and the dying trees have yellow or brown leaves or are completely dead. These articles speculate that the mortalities are due to summer drought and climate change in general being harsh on these kinds of trees that are accustomed to wet weather. There are also reports that other trees such as douglas firs and pine trees are facing similar circumstances.

These articles are relevant to the focus of my research paper because I am trying to determine the location of these trees to help identify what factors might be causing the decline of western redcedars.



Other texts:
https://bcitnews.com/2019/05/15/western-red-cedar-is-just-one-of-many-bc-trees-facing-extinction/
https://www.greenseattle.org/western-redcedar-die-off-in-seattle-parks
https://ppo.puyallup.wsu.edu/plant-health-concerns/redcedar/
https://www.oregon.gov/ODF/Documents/ForestBenefits/TreeDeclinesRedcedar.pdf
