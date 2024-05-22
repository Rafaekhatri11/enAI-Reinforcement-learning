# Fine-Tune FLAN-T5 with Reinforcement Learning (PPO) and PEFT to Generate Less-Toxic Summaries

This repository contains code and resources to fine-tune a FLAN-T5 model using reinforcement learning (PPO)(Proximal policy optimizer) and PEFT (parameter efficient fine tuning) to generate less-toxic summaries. The goal is to reduce the toxicity of generated content while maintaining coherence and relevance.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Fine-Tuning Process](#fine-tuning-process)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction

In this project, we aim to address the issue of toxic content generation by fine-tuning a pre-trained FLAN-T5 model using reinforcement learning techniques. By incorporating a reward model based on hate speech classification, we guide the model to produce less-toxic summaries while maintaining the quality of generated content.

## Setup

To run the code in this repository, you'll need to set up your environment with the required dependencies. Follow the instructions in the setup section to install the necessary packages and configure your environment.

## Fine-Tuning Process

The fine-tuning process involves several steps, including data preprocessing, model setup, reward model preparation, and optimization using Proximal Policy Optimization (PPO). Detailed instructions and code snippets for each step are provided in the repository.

## Evaluation

We evaluate the effectiveness of the fine-tuned model both quantitatively and qualitatively. Quantitative evaluation involves measuring the toxicity score of generated summaries before and after fine-tuning, while qualitative evaluation examines the coherence and relevance of the generated content.

## Results

The results of the fine-tuning process demonstrate a reduction in toxicity scores without significant degradation in content quality. We present both quantitative metrics and qualitative examples to illustrate the improvements achieved by the fine-tuned model.

