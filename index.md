## Differential Attention for Visual Question Answering
Badri Patro,Vinay P. Namboodiri
### Abstract
In this paper we aim to answer questions based on images when provided with a dataset of question-answer pairs for a number of images during training. A number of methods have focused on solving this problem by using image based attention. This is done by focusing on a specific part of the image while answering the question. Humans also do so when solving this problem. However, the regions that the previous systems focus on are not correlated with the regions that humans focus on. The accuracy is limited due to this drawback. In this paper, we propose to solve this problem by using an exemplar based method. We obtain one or more supporting and opposing exemplars to obtain a differential attention region. This differential attention is closer to human attention than other image based attention methods. It also helps in obtaining improved accuracy when answering questions. The method is evaluated on challenging benchmark datasets. We perform better than other image based attention methods and are competitive with other state of the art methods that focus on both image and questions.

### Motivation
-   We adopt an exemplar based approach to improve visual question answering (VQA) methods by providing a differential attention
-   We evaluate two variants for obtaining differential attention - one where we only obtain attention and the other where we obtain differential context in addition to attention
-    We show that this method correlates better with human attention and results in an improved visual question answering that improves the state-of-the-art for image based attention methods. It is also competitive with respect to other proposed methods for this problem.

### Introduction

![](images/cvpr_intro.png) 

### **VQA Models**

#### DAN Model 

![](images/cvpr_DAN.png) 

#### DCN Model 

![](images/cvpr_DCN.png) 



### Results
![](images/vqa_1.png) 

![](DCN_DAN_final_result.png)

![](Att_vis_final.png)

![](DCN_DAN_final_result_1.png)

![](DCN_DAN_final_result_2.png)


# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

