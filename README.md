# sbert-patent-classification

This project was completed under the guidance of Prof. Xiaochen Jing and Yuxuan Li at the University of Illinois 
as part of the Illinois Risk Lab. The slides used for the final presentation, which contains information about the
project, can be found [here](https://docs.google.com/presentation/d/1_rdYpsKrvwUjTKuJ-ne4XYrC1ZzGt6nbH-kBfz_aNzk/edit?usp=sharing).

### Overview

This project is a preliminary development on the paper "PatentSBERTa: A Deep NLP based Hybrid Model for Patent Distance and Classification using Augmented SBERT" (Bekamiri et al.).
It uses a featured subset of the data that they used. The primary innovation is to use classification at the section level to aid in classification at the subsection level. 
This modification has marginal benefits with the small sample size used in the notebook attached, but it is unclear how much it aids classification with a larger dataset.
Future experiments will verify whether this is a fruitful approach to problems like this.
