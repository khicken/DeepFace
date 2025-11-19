# DeepFace Mouse

This is a directory to two software tools used in ["DeepFace: A High-Precision and Scalable Deep Learning Pipeline for Predicting Large-Scale Brain Activity from Facial Dynamics in Mice"](https://pubmed.ncbi.nlm.nih.gov/40661434/).


<img width="1524" height="690" alt="image" src="https://github.com/user-attachments/assets/e5b59b96-dda3-415c-a42c-68f27daa6ae4" />


## [`mediaGUI`](https://github.com/khicken/mediaGUI)
Use this tool to preprocess gigabytes of facial video data to a single concatenated video, which is used to train DeepFace.

**Please see [mediaGUI](https://github.com/khicken/mediaGUI) for installation instructions.**

## [`sleapGUI`](https://github.com/khicken/sleapGUI)
This tool incorporates the optimized parameter combination specifically identified for large scale facial video analysis, enabling accurate and efficient large-scale orofacial data processing beyond the default SLEAP GUI.

**Please see [sleapGUI](https://github.com/khicken/sleapGUI) for installation instructions.**

## Comparision Video Between DeepFace Mouse, DeepLabCut (DLC), Facemap Basemodel, and Facemap Refined



https://github.com/user-attachments/assets/117a0c51-73cd-4746-b103-a9a76d137932



## Usage Demo
[DeepFace Tutorial Playist](https://youtu.be/w3Aq-whDUQ0)

## HPC Code
Attached here is the SLEAP based command lines that was used to do high performance computing analysis at Cleveland Clinic Lerner Research Institute using its avaliable GPU Type (A100) and Node Number (n = 2). 

[DeepFace_Mouse_HPC_Script.txt](https://github.com/user-attachments/files/23484367/DeepFace_Mouse_HPC_Script.txt)

## Troubleshoot
If you have a technical question with either [`mediaGUI`](https://github.com/khicken/mediaGUI) or [`sleapGUI`](https://github.com/khicken/sleapGUI), then feel free to request a "New Issue" in the "Issues" section for the respective GUI.

## Citation
If you use any components from this repository in your research, please cite the relevant publications associated with each module as specified in their respective README files.
