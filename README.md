# JengJeeng-r0

## Reasoning-Enhanced Pre-training of LLaMA-2-13B

This repository contains the code and resources for **Reasoning-Enhanced Pre-training (REP)** of the LLaMA-2-13B model. The goal of this project is to enhance the reasoning capabilities of the base LLaMA-2-13B model by fine-tuning it on datasets that emphasize logical reasoning, problem-solving, and structured thinking.

## Overview

The LLaMA-2-13B model is a powerful language model, but its reasoning capabilities can be further improved. This project focuses on pre-training the base model on reasoning-specific tasks, such as mathematical reasoning, code generation, and commonsense reasoning, to create a more robust and reasoning-enhanced version of the model.

### Key Features
- **Reasoning-Augmented Datasets**: Curated datasets focusing on logical reasoning, step-by-step problem-solving, and structured tasks.
- **Enhanced Pre-training**: Fine-tuning the LLaMA-2-13B model to improve its reasoning and cognitive abilities.
- **Evaluation Benchmarks**: Comprehensive evaluation on reasoning-specific benchmarks to measure improvements.

## Datasets
We use the following datasets for reasoning-enhanced pre-training:

- Mathematical Reasoning: [GSM8K](https://github.com/openai/grade-school-math), [MATH](https://github.com/hendrycks/math)

- Code Generation: [HumanEval](https://github.com/openai/human-eval)

- Commonsense Reasoning: [CommonsenseQA](https://www.tau-nlp.org/commonsenseqa), [ARC](https://allenai.org/data/arc)

- Logical Reasoning: [LogiQA](https://github.com/lgw863/LogiQA-dataset)

## Pre-training Process
- Data Preparation: Preprocess the reasoning datasets into a format suitable for pre-training.

- Fine-tuning: Fine-tune the LLaMA-2-13B model using the preprocessed datasets.

- Evaluation: Evaluate the model on reasoning benchmarks to measure improvements.