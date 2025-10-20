# Prompt Aggregation Dataset - Custom Dataset
This dataset is a curated collection of unsafe, adversarial, and sensitive prompts.

##  Overview  
This dataset is a curated collection of unsafe, adversarial, and sensitive prompts designed to support research in LLM safety, prompt injection defense, and content moderation. It aggregates diverse examples from multiple benchmark sources and hackathon experiments, enabling robust evaluation and training of safety filters and classifiers.

##  Structure  
The dataset includes:  
- **Prompt text**: Raw user inputs or adversarial instructions.   
- **Safety labels**: Optional annotations for unsafe/safe/sensitive classification.  

##  Download the Dataset

The full dataset is hosted on Hugging Face for easy access and download:

🔗 [Click here to view and download on Hugging Face](https://huggingface.co/datasets/dralsarrani/Prompt-Aggregation-Dataset-Custom-Dataset)

[![Download on Hugging Face](https://img.shields.io/badge/HuggingFace-Dataset-yellow?logo=huggingface)](https://huggingface.co/datasets/dralsarrani/Prompt-Aggregation-Dataset-Custom-Dataset)


##  Sources  
This dataset was compiled from the following public repositories and research efforts:  
- [chuyishang/safeguard](https://github.com/chuyishang/safeguard) – 2024 Berkeley AI Hackathon Repo  
- [JailbreakBench/artifacts](https://github.com/JailbreakBench/artifacts) – Jailbreak artifacts for JailbreakBench  
- [MurrayTom/SG-Bench](https://github.com/MurrayTom/SG-Bench) – SG-Bench: Evaluating LLM Safety Generalization Across Diverse Tasks and Prompt Types  
- [facebookresearch/fastText](https://github.com/facebookresearch/fastText) – Library for fast text representation and classification *(used for preprocessing and embedding tasks)*

##  Notes  
All data was collected and processed in accordance with the licenses of the original sources. Please refer to each repository for specific usage terms.

