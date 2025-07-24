# **CLIP Adaptation with PEFT Techniques**

## **Introduction**

The aim of this project is to implement a **PEFT** (Parameter Efficient Fine Tuning) technique for **CLIP \[1]** and to find a strategy to improve the baseline performance.
The chosen task for evaluation is a **base-to-novel classification task** on the **Flowers102** dataset.

The main technique explored is **CLIP-LoRA \[3]**, enhanced with a generative pipeline to create a synthetic dataset supporting the limited training set.
We reimplemented **DISEF \[4]**, evaluated its results, and attempted to improve its performance while reducing the computational cost of the generative process.

Before moving to this more complex approach, we implemented and evaluated:

* **CoCoOp \[2]**, a prompt tuning technique.
* **Vanilla CLIP-LoRA \[3]**.



## **Project Workflow**

The work is organized into the following steps:

1. **Evaluation of Zero-Shot CLIP**
2. **Evaluation of CoCoOp**
3. **Evaluation of CLIP-LoRA**
4. **Evaluation of DISEF** (an improvement on CLIP-LoRA)
5. **Evaluation of our improved DISEF**



## **References**

\[1] Radford et al. – CLIP
\[2] Zhou et al. – CoCoOp
\[3] Hu et al. – LoRA
\[4] Turrisi et al. – DISEF

