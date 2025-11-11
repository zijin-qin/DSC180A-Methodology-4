# DSC 180A MA4
Zijin Qin (z2qin@ucsd.edu)

Capstone section: A14 <br> Mentor: Tianhao Wang

# Quarter 2 Project Brainstorm Prompts
**What is the most interesting topic covered in your domain this quarter?**

This quarter, students in my domain were each assigned narrower topics to focus on. My topic was on the Muon optimizer, which I found interesting to explore. I am especially curious about how batch size influences the performance of the Muon optimizer because that is a subject I have not considered previously. 

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I want to build upon my investigation of the Muon optimizer this quarter while expanding into broader subjects of my domain. I want to explore which are the practical use cases that would benefit from the Muon optimizer and which would not benefit, such as testing Muon on language tasks, tabular data, or different datasets beyond the CIFAR-10 image dataset. I want to understand how the features learned by Muon differ across these data types.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

During Quarter 1, I've primarily implemented the Muon optimizer using a CNN model on CIFAR-10, focusing on the accuracy of the results compared to a pure AdamW baseline. One potential change in my approach on my current project that I would like to make is to understand the reasoning behind why the Muon optimizer improves accuracy yet takes slightly longer to run on a single GPU compared to improving both accuracy and efficiency on multiple GPUs in the original experiment described in the paper. 

**What other techniques would you be interested in using in your project?**

I'd be interested in exploring different model architectures beyond the CNN model. I want to test the Muon and AdamW hybrid model on various architectures such as ResNets and transformers, including exploring what each combination is ideal for in practice. To do so, I want to analyze the actual learned features in the Muon optimizer, building off of the exploration in how different metrics affect its accuracy in Quarter 1. 
