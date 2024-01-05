# MNetClass1.0.0: A noncontrol-dependent approach for microbiome subnetwork classification and central bacterial identification
## Introduction
`MNetClass` is a novel microbial network classification framework to classify the key subnetwork and identify central microbes at any body site using a random walk algorithm and rank-sum ratio-entropy weight evaluation model. <br>
The workflow of MNetClass is shown in the following Figure: (Details about this model can be found this paper.)
## News
- Nov, 2023: MNetClass version 1.0.0 is launched.
## Installation
- Prerequisites: MNetClass is developed under R (*version >= 3.6.1*).
- Latest version: The latest developmental version of MNetClass can be downloaded from GitHub and installed from source by `devtools::install_github('YihuaWWW/MNetClass')`
## Manual
Please see [MNetClass Tutorial](https://htmlpreview.github.io/?https://github.com/YihuaWWW/MNetClass/blob/master/vignettes/doc/Tutorial.html) for details. In the R terminal, please use the command `?MNetClass` to access the help documents.
## Data Requirements
Two types of data are needed to run the MNetClass:

- The relative abundance of microbial species in different individuals: tax_L7.txt
- The bipartite network made of correspondence reactions of species(or genus) towards phylum: phylum_species.txt 
## Example
In our [MNetClass Tutorial](https://htmlpreview.github.io/?https://github.com/YihuaWWW/MNetClass/blob/master/vignettes/doc/Tutorial.html), we applied this framework to analyze microbial features at tongue coating (T) of 21 volunteers as examples to show how to execute Scissor in real applications.
## How to cite `MNetClass`
Please cite the following manuscript:
> *MNetClass: A noncontrol-dependent approach for microbiome subnetwork classification and central bacterial identification(2023).<br>* *Yihua Wang, Qingzhen Hou, Fulan Wei, Bingqiang Liu and Qiang Feng*
## License
- MNetClass is licensed under the MIT License.
- Improvements and new features of MNetClass will be updated on a regular basis.
- If you have any questions or feedback, please contact Yihua Wang yihuawww@163.com.

