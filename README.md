# DLCryoTomo
**Hybrid neural network architecture**.
In this model, we extend semantic segmentation methods to automate the detection of membranes and vesicles in tomograms. This is achieved through a hybrid neural network architecture that combines the features of several architectures such as U-Net, DeepLab, SegNet, Gated-SCNN, Long Short-Term Memory (LSTM), and Recurrent Neural Network (RNN). Most importantly, we incorporate spatial and channel attention mechanisms, dilated convolutions, edge attention, and specific loss functions to enhance fine segmentation details. 
# How to use it
This project is intended to be run on Google Colab Pro due to its computational requirements (e.g., GPU acceleration, higher RAM, etc.).

Usage Instructions:
*Open the notebook file in Google Colab (recommended: Colab Pro account).

*Make sure to enable the GPU runtime if the code requires hardware acceleration.

*Before running the code, install the necessary libraries by executing the setup cells (if included), or manually by running:
