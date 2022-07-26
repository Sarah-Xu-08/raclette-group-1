# raclette-group-1

## Neuromatch Introduction

## Group Members
1. Xin Xu
2. Yukai Xu
3. Kai Fu
4. Vitto Resnick
5. Doris Zhang
6. Juee Dhar
7. Chetan Sharaf

Pod TA : Run Wang
Project TA : Vinsea Singh 
## Dataset Info 
## The Mindmap

## Abstract
# Subproject 1 
ECoG-based human motion prediction aims to predict future motion frames to guide various brain-computer interaction tasks. Most of the previous work has focused on solving this time series prediction task using RNN-based frameworks. However, RNN-based frameworks suffer from low spatial resolution problems, which means they can only utilize and provide little information about the spatial location of the electrodes and interactions between the brain areas where the electrodes are implanted in. Based on the fingerflex datasets (*Miller et al., 2009, 2012*) here, we propose a CNN-based prediction framework that not only shows promise in differentiating finger flexion movements, but also provides weighted spatial and functional information of electrodes that may account for the movement differences. Specifically, we use the 3-D format ECoG data as the input of the CNN model. Then, by performing Class Activation Mapping (CAM), we can get a weighted average of the feature maps in the last convolutional layer, from which we can localize which electrodes the model is focusing on based on the current fingerflex task. This can provide important information for neural computing, neurophysiological surgery, and neural circuit analysis.
# Subproject 2 
Visuospatial attention prioritizes the processing of visual inputs. According to previous research (*Benoni & Tsal, 2010*), there is a high possibility that the wrong response is caused by low attention levels or large attentional variations. In the ECoG-fingerflex dataset by *Miller, et al. (2009)*, we noticed that participants sometimes flex different fingers from what the cue on the screen asked.  Based on the wrong response subsets in the dataset, we assume that there is some modulation or switch in the attention state. Spectral-spatial patterns in dataset intersections’ across overlapping brain regions may pinpoint regions related to the finger-flexion preparation and execution. An investigation of the participants' response time is fairly standard in the study of attention, which helps visualize patterns, discrepancies, and trade-offs in accuracy discreetly. Additionally, attention could also be characterized by the spatial-temporal dynamics of the alpha oscillation (8-14Hz). The increase in alpha activity has been associated with a loss in attentional load. Meanwhile, it is believed that synchronization between frontal and parietal areas acts as a general mechanism for the detection of attention levels. We use the response time (RT), alpha-band activity and the synchronization between frontal and parietal areas as the criteria for the correlation between the attentional level and correct/wrong response. 

## Result

## Mentor Meeting Slide Link

## Reference
data reference:
Miller, Kai J., et al. "Decoupling the cortical power spectrum reveals real-time representation of individual finger movements in humans." Journal of Neuroscience 29.10 (2009): 3132-3137.
Miller, Kai J., et al. "Human motor cortical activity is selectively phase-entrained on underlying rhythms." (2012): e1002655.
