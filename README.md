# **SAE Feature Interpretation and Activation Editing – Notebook**

This repository contains a commented Jupyter notebook designed to explore, interpret, and manipulate **Sparse Autoencoder (SAE)** features inside a Large Language Model.  
The notebook demonstrates how to:

- Inspect SAE latent vectors  
- Generate human-interpretable explanations for features  
- Modify activations by amplifying or clamping individual latent dimensions  
- Observe downstream effects on model outputs  
- Use framework Delphi, token-change-based and vocabulary-projection-based explanations to infer the meaning of features  

The notebook is fully annotated and intended as an educational resource for understanding mechanistic interpretability workflows with SAEs.

---


## **📦 Requirements**

The notebook depends on the following libraries:

1. **sae_lens**  
   GitHub: https://github.com/ale29ruf/sae_lens.git

2. **EleutherAI/delphi**  
   GitHub: https://github.com/godSaveDaniele/progetto_nlp_2.git

3. **EleutherAI/sparsify**  
   Installable via pip:
   ```bash
   pip install sparsify
