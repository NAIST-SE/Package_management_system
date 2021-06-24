# Package_management_system
# Research Artifact: Choice Matters: Contrasting Package Manager User Experience
[https://github.com/syful-is/Package_management_system.git](https://github.com/syful-is/Package_management_system.git)

## Abstract
A package manager (PM) is crucial to most technology stacks, acting as a broker to ensure that a verified dependency package is correctly installed, configured, or removed from an application. Diversity in technology stacks has led to dozens of PMs with various features.
While recent studies have shown that developers struggle to migrate their dependencies, the common assumption is that PMs are used without any issue. 
In this study, we explore sixteen PMs to understand whether their features correlate with the experience of their users.
By studying experience through the questions that developers ask on the question-and-answer site Stack Overflow, we find that developer questions are  grouped into three themes (i.e., PM management, Input-Output, and Package Usage). Our analysis results indicate that specific features are correlated with the user experience.
Our work lays out future directions to investigate the trade-offs involved in designing the ideal PM.
    
## Replication package Structure:
```
📁 Package Management project/
├─ 📁 Dataset/
├─ 📁 Scripts/ 
├─ 📁 Results/
─
```
## Contents:
  1. [Dataset](https://github.com/syful-is/Package_management_system/tree/master/Dataset)- is a folder that contains the dataset for `PM project`.
  2. [Scripts](https://github.com/syful-is/Package_management_system/tree/master/Scripts)- is a folder that contains the all the codes. 
  3. [Results](https://github.com/syful-is/Package_management_system/tree/master/Results)- is a folder that contains the results obtained from dataset.

## How to run:
  1. Clone the repository from [here](https://github.com/syful-is/Package_management_system.git) and the Dataset from [here](https://github.com/syful-is/Package_management_system/tree/master/Dataset)
  2. Extract the files.
  3. Open `Jupyter Notebook` or `Python Spyder`.
  4. Copy any code and Set your working directory using 
                
                ```
                import os
                
                #Please specify your dataset directory. 
                os.chdir("..../Dataset/")
                ```
  
  4. Example-1: Run the LDA topic modeling **[LDA_Topic_modeling.ipynb](https://github.com/syful-is/Package_management_system/blob/master/Scripts/2.%20Topic_modeling/LDA_Topic_modeling.ipynb)** 

## Authors:
1. [Syful Islam](https://syful-is.github.io/), Nara Institute of Science and Technology (NAIST), Nara, Japan.
2. [Raula Gaikovina Kula](https://raux.github.io/), Nara Institute of Science and Technology (NAIST), Nara, Japan.
3. [Christoph Treude](http://ctreude.ca/), University of Adelaide, Adelaide, Australia.
4. [Takashi Ishio](https://takashi-ishio.github.io/), Nara Institute of Science and Technology (NAIST), Nara, Japan.
5. [Kenichi Matsumoto](http://isw3.naist.jp/Contents/Research/cs-05-en.html), Nara Institute of Science and Technology (NAIST), Nara, Japan.



  
## MIT License for code
Our SZZ implementation is licensed under the [MIT License](LICENSE).

## CC0 1.0 Universal for dataset
CC0 [summary](https://creativecommons.org/publicdomain/zero/1.0/) and [legal text](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

Our dataset are published on the public domain, so that anyone may freely build upon, enhance and reuse the dataset for any purposes without restriction under copyright or database law.
