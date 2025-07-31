# 🧠 S2EA-Net

This repository provides the **PyTorch implementation** of the paper:  
**Towards Expert-Level EEG-Based Depression Detection: A Self-constructing Sparse Energy-Aware Framework Using ARMA-GNN**

> 📌  **Status**: *Under review*
> 📌  **Paper Link**: *Coming soon*

***************************************************************************

> **Abstract:** Topological analysis methods based on graph neural networks have shown significant potential in the field of depression detection. However, due to the significant nonlinearity and high temporal variability of EEG signals, existing methods face limitations in modeling multi-channel EEG data and struggle to effectively learn complex topological patterns. In this context, we propose a novel multi-channel topological analysis method, called S2EA-Net. Specifically, by integrating energy distribution patterns with the Top-U channel selection strategy, we design a self-constructing sparse topological network that dynamically generates an energy-aware adjacency matrix. This approach adaptively adjusts the topological structure, highlights key connectivity pathways, minimizes redundant information interference, and enhances the expressive quality of multi-channel EEG signals. Next, we establish a multi-scale topological feature extraction network based on k-order recursive ARMA filters and graph neural network. Unlike traditional fixed polynomial filters, we compute multiple low-order recursive filters in parallel to approximate the effect of high-order filters, thereby enabling more flexible frequency response adjustment. This strategy enhances the model’s ability to jointly capture local and global information. We verify the effectiveness of the method on the publicly available datasets of HUSM and MODMA. We map the features onto brain topography and observe abnormal activities in regions associated with the FP1, FP2, T3, and T4 electrodes. By visualizing connectivity strength, we demonstrate that our model can reveal underlying multi-channel connection patterns. This method provides new insights for the personalized diagnosis of depression.
***************************************************************************

### Illustration
<div align=center>
<img src="[[https://github.com/YuhangLiu98/SDCNN/blob/main/img/SDCNN.png](https://github.com/XC-Posi/S2EA-Net/blob/main/S2EA-Net-Architecture.png)](https://github.com/XC-Posi/S2EA-Net/blob/main/S2EA-Net-Architecture.png" width="800"/> 
</div>
