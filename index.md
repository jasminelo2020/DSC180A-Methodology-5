# Jasmine Lo ([j2lo@ucsd.edu](j2lo@ucsd.edu))

## Section B01: Robust and Interpretable Neural Network Models for Computer Vision and Natural Language Processing
### Mentor: Lily Weng

**What is the most interesting topic covered in your domain this quarter?**\
The most interesting topic covered in my domain this quarter was the different similarity functions used to classify the intermediate neurons. It was interesting to me how each of these could change the accuracy of each layers' labels so much. SoftWPMI is the best out of the different similarity functions we have used, and it was interesting breaking down how it differs from WPMI (Weighted Pointwise Mutual Information) and the other similarity functions. It was cool to look at the different mathematical formulas for each of these similarity functions. I also saw the the simple functions like cosine similarity did not perform so well, especially against the softWPMI function, because of the high weight placed on inputs that didn't activate the neuron highly.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**\
A potential investigation that I would like to pursue in my Quarter 2 Project is to understand potential uses of CLIP-Dissect. I want to know what questions people have when they are introduced to this concept of understanding individual neurons in a deep neural network, and build a tool that could be used by anyone to better understand CLIP-Dissect's method and findings. I want to figure out a more general usage of CLIP-Dissect and provide the medium to do so.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**\
A potential change that I would make to my approach tken in my current Quarter 1 Project is to be do more hands-on work. Rather than doing the same neuron labeling over and over for different similarity functions and concept sets, I would like to use the data I have already collected and do some analyses on them. Maybe we can figure out the best combination and then dissect that combination to figure out why it performed the best. It would also be cool to actually work with CLIP-Dissect directly and understand that model. Maybe there is some insight that I might be missing from not looking at the CLIP-Dissect method directly.

**What other techniques would you be interested in using in your project?**\
I would be interested in using CLIP-Dissect but with some areas tweaked. For example, what if some neurons or inputs were turned off? How would this affect our end result? What changes are made for different questions that are posed? I am also interested in looking into the [label free CBM](https://github.com/Trustworthy-ML-Lab/Label-free-CBM) method, and looking at interpretable vs uninterpretable neurons and seeing if dropping the uninterpretable ones might improve our accuracy.
