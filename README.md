
# Microbiome 617 - Analyzing Microbiome Data 


By the end of our two classes you'll (hopefully!) get a better grasp of how to go from raw 16S sequences to biologically informative conclusions 




## 16S rRNA Analysis Overview: 

A general overview how to analyze 16S rRNA gene sequencing!

I'll provide info on all the steps below in the lecture, but the hands-on sessions will largely focus on library size normalization, calculating ecological distance, and generating ordination/relative abundance plots. 

The goal here is not to go through every step in excruciating detail but to give you an overview of the workflow, understand the biology, and some of the aspects of the pipeline that are universal to microbial ecology analyses




![image](https://github.com/user-attachments/assets/2971fe51-d085-4bae-8966-9ce372b88bcf)


## Dataset to be analyzed: 

Ecological dynamics of the gut microbiome in response to dietary fiber: Liu et al., 2022 (ISME): https://www.nature.com/articles/s41396-022-01253-4#code-availability

Feel free to read the paper before the classes, but no need to. Since we are "re" analyzing the dataset, there will be spoilers if you do read it!

Raw read files deposited in NCBI SRA: PRJNA754019

A relatively simple and (interesting) 16S dataset! 

Dataset Overview: 

![image](https://github.com/user-attachments/assets/22a4868b-710d-4069-99b9-637b9acbe6c1)

To simplify the dataset we will only work with a fraction of samples: time 0, time 5, time 13 and time 31. (Samples from Hunan are also removed here)





