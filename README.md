# FocalPO: Enhancing Preference Optimizing by Focusing on Correct Preference Rankings

Offical code for the paper [FocalPO: Enhancing Preference Optimizing by Focusing on Correct Preference Rankings](https://arxiv.org/abs/2501.06645) (ACL 2025 long paper).


<img width="400" alt="image" src="https://github.com/user-attachments/assets/698d8854-7b88-4e51-aea5-a809147c4ef8" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/7be2e1d6-e1b3-4366-a673-a7c532424fa0" />

<h2> Released Models </h2>  
<h3> Mistral </h3>  

We release the following model that are built on top of [Mistral-Base SFT (7B)](https://huggingface.co/HuggingFaceH4/mistral-7b-sft-beta) model by training FocalPO on [UltraFeedback](https://huggingface.co/datasets/trl-lib/ultrafeedback_binarized) dataset.   

|               models                    |  Alpaca Eval 2.0 LC |  AH WR | 
|-----------------------------------|:------:|:------:|
|        [tongliuphysics/Mistral-7B-Base-SFT-FocalPO](https://huggingface.co/tongliuphysics/Mistral-7B-Base-SFT-FocalPO)       |  23.9  | 17.1 | 

<h3> Llama </h3>  

We release the following model that are built on top of [Llama-3-Instruct (8B)](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) model by training FocalPO on the on-policy [Llama3-ultrafeedbackarmorm](https://huggingface.co/datasets/princeton-nlp/llama3-ultrafeedback-armorm) dataset.   

|               models                    | Alpaca Eval 2.0 LC |  AH WR | 
|-----------------------------------|:------:|:------:|
|        [tongliuphysics/Llama-3-8B-Instruct-FocalPO](https://huggingface.co/tongliuphysics/Llama-3-8B-Instruct-FocalPO)       |  54.7   | 34.6 | 


<h2> BibTeX </h2>  

```bash
@article{liu2025focalpo,
  title={FocalPO: Enhancing Preference Optimizing by Focusing on Correct Preference Rankings},
  author={Liu, Tong and Yu, Xiao and Zhou, Wenxuan and Gu, Jindong and Tresp, Volker},
  journal={arXiv preprint arXiv:2501.06645},
  year={2025}
}

```   

