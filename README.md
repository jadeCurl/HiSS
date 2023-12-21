# HiSS: Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method (AACL 2023)

Official implementation of paper "[Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method](https://arxiv.org/abs/2310.00305)".

## Introduction

1. We introduce a Hierarchical Step-by-Step (HiSS) prompting method which directs LLMs to separate a claim into several subclaims and then verify each of them via multiple questions-answering steps progressively.

2. Experiment results on two public misinformation datasets show that HiSS prompting outperforms state-of-the-art fully-supervised approach and strong few-shot ICL-enabled baselines.

## Datasets

This repository uses data from the [RawFC](https://github.com/Nicozwy/CofCED/tree/main/Datasets/RAWFC) and [LIAR](https://huggingface.co/datasets/liar) datasets. 

## Setup

1. Obtain an OpenAI API key and save it to the environment variable `OPENAI_API_KEY`.

2. Obtain a [SerpApi](https://serpapi.com/) key and save it to the environment variable `SERPAPI_KEY`.
   
## Citation

If you find HiSS helpful or intriguing and decide to use it, kindly acknowledge the paper by citing it and consider starring this repo, thanks!

```bibtex
@misc{zhang2023llmbased,
      title={Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method}, 
      author={Xuan Zhang and Wei Gao},
      year={2023},
      eprint={2310.00305},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
