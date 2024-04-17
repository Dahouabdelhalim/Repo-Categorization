# Repo-Categorization

# Automatic Categorization of Software Repositories

This repository hosts the code and dataset related to our research on the automatic categorization of software repositories into predefined domains using minimal resources. Our approach leverages few-shot learning techniques and language models to categorize repositories effectively, even with limited training data.

## Abstract

In this project, we develop a classification model that categorizes software repositories by analyzing both high-level and low-level features of the repository content. This approach helps in systematically grouping software, aiding developers in locating and utilizing repositories more efficiently. Our model employs advanced ML techniques to deal with data challenges typically associated with software repositories.

## Keywords

- Software Categorization
- Few-Shot Learning
- Language Model
- Data Augmentation
- R Code

## Repository Structure

- `/data`: Includes the dataset collected from Zenodo, segmented into training and testing sets.
- `README`: Documentation and additional resources related to the project.
- `/scripts`: Utility scripts for training, inferencing and make API calls.

## Citation

If you use our work or dataset in your research, please cite our paper:

```bibtex
@conference{kdir23,
  author = {Abdelhalim Dahou and Brigitte Mathiak},
  title = {Subject Classification of Software Repository},
  booktitle = {Proceedings of the 15th International Joint Conference on Knowledge Discovery, Knowledge Engineering and Knowledge Management - Volume 1: KDIR},
  year = {2023},
  pages = {30-38},
  publisher = {SciTePress},
  organization = {INSTICC},
  doi = {10.5220/0012159600003598},
  isbn = {978-989-758-671-2}
}
