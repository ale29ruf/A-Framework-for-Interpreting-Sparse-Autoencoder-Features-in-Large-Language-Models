# **SAE Feature Interpretation and Activation Editing – Notebook**

This repository contains a commented Jupyter notebook designed to explore, interpret, and manipulate **Sparse Autoencoder (SAE)** features inside a Large Language Model.  
The notebook demonstrates how to:

- Inspect SAE latents  
- Generate human-interpretable explanations for features  
- Modify latent activations by amplifying or clamping
- Observe downstream effects on model outputs  
- Use framework Delphi, token-change-based and vocabulary-projection-based explanations to infer the meaning of features
- **Evaluate the quality of feature explanations through metrics**

The notebook is fully annotated and intended as an educational resource for understanding mechanistic interpretability workflows with SAEs.

---

## **📚 Additional Notebooks and Experiments**

This repository also includes (or refers to) several additional notebooks containing deeper experiments and extended analyses.  
These complementary resources explore:

- **Advanced explanation generation techniques**  

- **Feature steering experiments**  

- **Extended evaluation metrics**  

These notebooks provide further insight into the interpretability pipeline and offer additional experimental material beyond the main workflow.

If you are interested in accessing these supplementary notebooks, discussing the experiments, or exploring potential collaborations,  
**feel free to contact me privately.**



## **📦 Requirements**

The notebook depends on the following libraries:

1. **sae_lens**  
   GitHub: https://github.com/ale29ruf/sae_lens.git

2. **EleutherAI/delphi**  
   GitHub: https://github.com/godSaveDaniele/progetto_nlp_2.git

3. **EleutherAI/sparsify**  
   Installable via pip:
   ```bash
   pip install eai-sparsify
