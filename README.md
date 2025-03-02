# A Dataset for the Detection of Dehumanizing Language
This repository contains both the unlabeled and labeled data for the paper [A Dataset for the Detection of Dehumanizing Language](https://aclanthology.org/2024.ltedi-1.2) (Engelmann et al., LTEDI-WS 2024)

## Labeled dataset
The labeled dataset contains the annotations from both annotators. 
Each row is marked with a 1 in the applicable column depending on if annotators see a sample as dehumanizing / not dehumanizing / unsure. 
Not applicable columns for a sample are left blank.

The data contains both the annotations before and after the discussion. The first 600 samples were annotated before the discussion, the remaining after. This was marked through additional columns.

## Unlabeled dataset
The unlabeled dataset was split into two halves (unlabeled_dataset_first.json and unlabeled_dataset_second.json) to accommodate for data upload size restrictions. 
After cloning the repository, the unlabeled dataset can be concatenated to retrieve the original data used in the paper.