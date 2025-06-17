# DLCryoTomo
**Hybrid neural network architecture**.
In this model, we extend semantic segmentation methods to automate the detection of membranes and vesicles in tomograms. This is achieved through a hybrid neural network architecture that combines the features of several architectures such as U-Net, DeepLab, SegNet, Gated-SCNN, Long Short-Term Memory (LSTM), and Recurrent Neural Network (RNN). Most importantly, we incorporate spatial and channel attention mechanisms, dilated convolutions, edge attention, and specific loss functions to enhance fine segmentation details. 
# How to use it
## 💻 Running the Code
This project is intended to be run on **[Google Colab Pro](https://colab.research.google.com/)** due to the computational resources required (e.g., GPU acceleration, extended RAM, etc.).
### 🚀 Usage Instructions
1. Open the notebook file directly in [Google Colab](https://colab.research.google.com/).
2. It is **recommended to use a Colab Pro account** for better performance and hardware access.
3. Enable the **GPU runtime** by going to:
   - `Runtime` → `Change runtime type` → Select **GPU**
