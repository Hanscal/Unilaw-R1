# Unilaw-R1
> The official implementation for the paper *Unilaw-R1: A Large Language Model for Legal Reasoning with Reinforcement Learning and Iterative Inference*, in EMNLP2025.

<img src="https://img.shields.io/badge/Venue-EMNLP--2025-278ea5" alt="venue"/> <img src="https://img.shields.io/badge/Status-Accepted-success" alt="status"/> <img src="https://img.shields.io/badge/Issues-Welcome-red"> <img src="https://img.shields.io/badge/Last%20Updated-2025--08--28-2D333B" alt="update"/>

## Usage

### Dependencies

Install the required libraries (Python 3.9.21 | CUDA 12.4)

```sh
pip install -r requirements.txt 
```

### Dataset

- **Training Data**  
    The JEC-QA dataset consists of objective question-answering entries in the legal domain. This dataset, along with our primary dataset, has been distilled and partitioned into the Unilaw-R1-Data (SFT) and RL subsets.

- **Evaluation Data**  
    The Unilaw-R1-Eval dataset comprises 800 curated comparative question-answer pairs, which we have further refined in a fine-grained and domain-relevant manner.

    Additionally, the following two evaluation datasets are used:  
    - [LawBench](https://github.com/open-compass/LawBench)  
    - [LexEval](https://github.com/cshaitao/lexeval)

### checkpoint
We have open-sourced the **Unilaw-R1** model weights solely for academic exploration only.  
**This is a low‑cost, low‑parameter baseline model, not a production-grade model.** 
The weights are available for download from [Baidu Netdisk]([https://pan.baidu.com/s/1xNt3qFFUgo5xcTOI9wS5NA?pwd=3528]) (passcode: **3528**).   

### To-Do (Coming Soon ~)
 - release inference code.
 - release training code.

## Citation
If you find our work useful for your research, please kindly cite our paper as follows:
```
@article{unilaw-r12025,
  title={Unilaw-r1: A large language model for legal reasoning with reinforcement learning and iterative inference},
  author={Cai, Hua and Zhao, Shuang and Zhang, Liang and Shen, Xuli and Xu, Qing and Shen, Weilin and Wen, Zihao and Ban, Tianke},
  booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
  pages={18128--18142},
  year={2025}
}
```
