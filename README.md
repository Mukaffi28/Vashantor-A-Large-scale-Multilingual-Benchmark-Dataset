# Vashantor: A Large-scale Multilingual Benchmark Dataset for Automated Translation of Bangla Regional Dialects to Bangla Language

## Abstract
The Bangla linguistic variety is a fascinating mix of regional dialects that adds to the culturaldiversity of the Bangla-speaking community. Despite extensive study into translating Banglato English, English to Bangla, and Banglish to Bangla in the past, there has been a noticeablegap in translating Bangla regional dialects into standard Bangla. In this study, we set out tofill this gap by creating a collection of 32,500 sentences, encompassing Bangla, Banglish,and English, representing five regional Bangla dialects. Our aim is to translate these regionaldialects into standard Bangla and detect regions accurately. To achieve this, we proposedmodels known as mT5 and BanglaT5 for translating regional dialects into standard Bangla.Additionally, we employed mBERT and Bangla-bert-base to determine the specific regionsfrom where these dialects originated. Our experimental results showed the highest BLEUscore of 69.06 for Mymensingh regional dialects and the lowest BLEU score of 36.75 forChittagong regional dialects. We also observed the lowest average word error rate of 0.1548for Mymensingh regional dialects and the highest of 0.3385 for Chittagong regional dialects.For region detection, we achieved an accuracy of 85.86% for Bangla-bert-base and 84.36%for mBERT. This is the first large-scale investigation of Bangla regional dialects to Banglamachine translation. We believe our findings will not only pave the way for future work onBangla regional dialects to Bangla machine translation, but will also be useful in solvingsimilar language-related challenges in low-resource language conditions. 

## Table of Contents
- [Experimental Setups](#experimental-setups)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Dataset Availability](#dataset-availability)
- [Results](#results)
- [Citation](#citation)
- [Contact Information](#contact-information)
- [Future Work](#future-work)

## Experimental Setups

### Setup 1: Google Colaboratory
- **Environment:**
  - Python Version: 3.10.12
  - PyTorch Version: 2.0.1
  - GPU: Tesla T4 (15 GB)
  - RAM: 12.5 GB
  - Disk Space: 64 GB

### Setup 2: Jupyter Notebook Environment
- **Environment:**
  - Python Version: 3.10.12
  - PyTorch Version: 2.0.1
  - GPU: NVIDIA GeForce RTX 3050 (8 GB)
  - RAM: 16 GB
  - Storage: 512 GB NVMe SSD

## Usage
Provide examples of how to use your code. Include sample inputs and expected outputs.

## Folder Structure
Explain the organization of your codebase. Outline the purpose of each major folder or module.

## Dataset Availability

The "Vashantor" dataset, available in both CSV and JSON formats, is now publicly accessible. This dataset provides users with a valuable opportunity for flexible exploration and utilization in various research and analysis endeavors. You can explore and download the dataset at the following link: [Vashantor Dataset](https://data.mendeley.com/datasets/bj5jgk878b/2) Feel free to leverage this resource for your research, experiments, or any other analytical purposes. If you have any questions or need further assistance with the dataset, don't hesitate to reach out.

## Results
### CER, WER, BLEU, METEOR scores of all the Bangla regional dialect translation models

| Region       | Model    | CER    | WER    | BLEU   | METEOR |
|--------------|----------|--------|--------|--------|--------|
| Chittagong   | mT5      | 0.2308 | 0.3959 | 36.75  | 0.6008 |
| Chittagong   | BanglaT5 | 0.2040 | 0.3385 | 44.03  | 0.6589 |
| Noakhali     | mT5      | 0.2035 | 0.3870 | 37.43  | 0.6073 |
| Noakhali     | BanglaT5 | 0.1863 | 0.3214 | 47.38  | 0.6802 |
| Sylhet       | mT5      | 0.1472 | 0.2695 | 51.32  | 0.7089 |
| Sylhet       | BanglaT5 | 0.1715 | 0.2802 | 51.08  | 0.7073 |
| Barishal     | mT5      | 0.1480 | 0.2644 | 48.56  | 0.7175 |
| Barishal     | BanglaT5 | 0.1497 | 0.2459 | 53.50  | 0.7334 |
| Mymensingh   | mT5      | 0.0796 | 0.1674 | 64.74  | 0.8201 |
| Mymensingh   | BanglaT5 | 0.0823 | 0.1548 | 69.06  | 0.8312 |

These results represent the evaluation metrics (CER, WER, BLEU, METEOR) for different regions using the mT5 and BanglaT5 models. Explore the performance of each model across various linguistic regions.


## Citation
Include a citation or link to your research paper if it's published. If not yet published, mention the anticipated publication venue or status.

## Contact Information
Include your contact information or ways for others to reach out if they have questions or want to collaborate.


## Future Work
 


