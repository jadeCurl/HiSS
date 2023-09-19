# HiSS: Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method (AACL 2023)

Official implementation of paper "Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method".

## Introduction

1. We introduce a Hierarchical Step-by-Step (HiSS) prompting method which directs LLMs to separate a claim into several subclaims and then verify each of them via multiple questions-answering steps progressively.

2. Experiment results on two public misinformation datasets show that HiSS prompting outperforms state-of-the-art fully-supervised approach and strong few-shot ICL-enabled baselines.

## Datasets

This repository uses data from the [RawFC](https://github.com/Nicozwy/CofCED/tree/main/Datasets/RAWFC) and [LIAR](https://huggingface.co/datasets/liar) datasets. 

## Setup

First, obtain an OpenAI API key and save it to the environment variable `OPENAI_API_KEY`.

## Citation

TBD
