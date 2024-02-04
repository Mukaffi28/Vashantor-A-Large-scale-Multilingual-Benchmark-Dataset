# Vashantor: A Large-scale Multilingual Benchmark Dataset for Automated Translation of Bangla Regional Dialects to Bangla Language

## Abstract
The Bangla linguistic variety is a fascinating mix of regional dialects that adds to the culturaldiversity of the Bangla-speaking community. Despite extensive study into translating Banglato English, English to Bangla, and Banglish to Bangla in the past, there has been a noticeablegap in translating Bangla regional dialects into standard Bangla. In this study, we set out tofill this gap by creating a collection of 32,500 sentences, encompassing Bangla, Banglish,and English, representing five regional Bangla dialects. Our aim is to translate these regionaldialects into standard Bangla and detect regions accurately. To achieve this, we proposedmodels known as mT5 and BanglaT5 for translating regional dialects into standard Bangla.Additionally, we employed mBERT and Bangla-bert-base to determine the specific regionsfrom where these dialects originated. Our experimental results showed the highest BLEUscore of 69.06 for Mymensingh regional dialects and the lowest BLEU score of 36.75 forChittagong regional dialects. We also observed the lowest average word error rate of 0.1548 for Mymensingh regional dialects and the highest of 0.3385 for Chittagong regional dialects.For region detection, we achieved an accuracy of 85.86% for Bangla-bert-base and 84.36%for mBERT. This is the first large-scale investigation of Bangla regional dialects to Banglamachine translation. We believe our findings will not only pave the way for future work onBangla regional dialects to Bangla machine translation, but will also be useful in solvingsimilar language-related challenges in low-resource language conditions. 

## Table of Contents
- [Experimental Setups](#experimental-setups)
- [Dataset Availability](#dataset-availability)
- [Results](#results)
- [Citation](#citation)
- [Contact Information](#contact-information)

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

### Performance Overview of all region detection models

| Model              | Accuracy | Log Loss | Region       | Precision | Recall  | F1-Score |
|---------------------|----------|----------|--------------|-----------|---------|----------|
| mBERT              | 84.36%   | 0.9549   | Chittagong   | 0.8779    | 0.8058  | 0.8913   |
|                    |          |          | Noakhali     | 0.9286    | 0.9437  | 0.9361   |
|                    |          |          | Sylhet       | 0.7304    | 0.9013  | 0.8072   |
|                    |          |          | Barishal     | 0.8187    | 0.5893  | 0.6847   |
|                    |          |          | Mymensingh   | 0.9412    | 0.968   | 0.9544   |
| Bangla-bert-base   | 85.86%   | 0.8804   | Chittagong   | 0.884     | 0.8486  | 0.8651   |
|                    |          |          | Noakhali     | 0.9625    | 0.9301  | 0.9461   |
|                    |          |          | Sylhet       | 0.7388    | 0.9147  | 0.8173   |
|                    |          |          | Barishal     | 0.8373    | 0.616   | 0.7091   |
|                    |          |          | Mymensingh   | 0.9599    | 0.9653  | 0.9626   |

These metrics showcase the performance of mBERT and Bangla-bert-base models in terms of accuracy, log loss, precision, recall, and F1-score across different regions.

## Contact Information

For any questions, collaboration opportunities, or further inquiries, please feel free to reach out:

- **Fatema Tuj Johora Faria**
  - Email: [fatema.faria142@gmail.com](mailto:fatema.faria142@gmail.com)

- **Mukaffi Bin Moin**
  - Email: [mukaffi28@gmail.com](mailto:mukaffi28@gmail.com)

- **Tashreef Muhammad**
  - Email: [tashreef.muhammad@seu.edu.bd](mailto:tashreef.muhammad@seu.edu.bd)
    
## Citation

If you find the "Vashantor" dataset or the associated research work helpful, please consider citing our paper:

```bibtex
@misc{faria2023vashantor,
  title={Vashantor: A Large-scale Multilingual Benchmark Dataset for Automated Translation of Bangla Regional Dialects to Bangla Language},
  author={Fatema Tuj Johora Faria and Mukaffi Bin Moin and Ahmed Al Wase and Mehidi Ahmmed and Md. Rabius Sani and Tashreef Muhammad},
  year={2023},
  eprint={2311.11142},
  archivePrefix={arXiv},
  primaryClass={cs.CL}
}






 


