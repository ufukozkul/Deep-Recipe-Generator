# Deep-Recipe-Generator
Deep Recipe Generator (DRG) is a novel AI-powered tool designed to reduce food waste by generating creative and informative recipes from discarded or available ingredients. Built on the LLaMA 2-7B model and fine-tuned using LoRA (Low-Rank Adaptation), DRG achieves high computational efficiency and provides detailed recipes, including nutritional values and preparation steps. This repository contains the implementation, dataset preprocessing scripts, training configurations, and evaluation results.

## Overview
The **Deep Recipe Generator (DRG)** is an AI-driven system that helps minimize food waste by generating recipes based on available or discarded ingredients. Using the LLaMA 2-7B model and LoRA (Low-Rank Adaptation) for fine-tuning, DRG achieves efficient training while maintaining high-quality recipe generation.

### Features
- **Ingredient-Based Recipe Generation**: Input a list of ingredients, and DRG generates detailed recipes.
- **Nutritional Information**: Provides preparation time, calories, and other nutritional details.
- **Parameter-Efficient Training**: Utilizes LoRA to significantly reduce training computational costs.

## Key Components
1. **Dataset**: iFood Recipe dataset with over 230K recipes.
2. **Model**: LLaMA 2-7B pre-trained large language model.
3. **Fine-Tuning Method**: LoRA for low-rank adaptation.
4. **Evaluation Metrics**: BLEU, ROUGE, and human evaluators for performance analysis.


## References
- Paper: [Deep Recipe Generator](https://github.com/ufukozkul/Deep-Recipe-Generator/blob/main/DeepRecipeGenerator.pdf)
