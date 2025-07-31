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
<img src="https://github.com/XC-Posi/S2EA-Net/blob/main/S2EA-Net-Architecture.png" width="800"/>
</div>

### DATASET

1.HUSM Dataset   
Please refer to: Mumtaz W, Xia L, Mohd Yasin M A, et al. A wavelet-based technique to predict treatment outcome for major depressive disorder[J]. PloS one, 2017, 12(2): e0171409.

2.MODMA Dataset   
Please refer to: Cai H, Yuan Z, Gao Y, et al. A multi-modal open dataset for mental-disorder analysis[J]. Scientific Data, 2022, 9(1): 178.

### Data preprocessing
For the data preprocessing tools, please refer to: Delorme A., Makeig S., EEGLAB: an open source toolbox for analysis of single-trial EEG dynamics including independent component analysis[J]. Journal of Neuroscience Methods, 2004, 134:9-21.

### Visualization
<div align=center>
<img src="https://github.com/XC-Posi/S2EA-Net/blob/main/Comparison-of-topography.png" width="800"/>
</div>

For visualization tools, please refer to: Gramfort A., Luessi M., Larson E., Engemann D.A., Strohmeier D., Brodbeck C., Parkkonen L., Hämäläinen M.S., MNE software for processing MEG and EEG data[J]. Neuroimage, 2014, 86:446-460.
or: https://mne.tools/stable/index.html.
