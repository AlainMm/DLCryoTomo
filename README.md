# DLCryoTomo
**Hybrid neural network architecture**.
In this model, we extend semantic segmentation methods to automate the detection of membranes and vesicles in tomograms. This is achieved through a hybrid neural network architecture that combines the features of several architectures such as U-Net, DeepLab, SegNet, Gated-SCNN, Long Short-Term Memory (LSTM), and Recurrent Neural Network (RNN). Most importantly, we incorporate spatial and channel attention mechanisms, dilated convolutions, edge attention, and specific loss functions to enhance fine segmentation details. 
# How to use it
## 💻 Running the Code

This notebook is self-contained and includes all the necessary installation commands to set up the environment.

### 🚀 Usage Options

You can run the notebook using either of the following platforms:

#### ✅ Option 1: Google Colab

1. Open the notebook directly in [Google Colab](https://colab.research.google.com/).
2. (Optional) If your task is resource-intensive (e.g., deep learning), enable GPU:
   - Go to `Runtime` → `Change runtime type` → Select **GPU**
3. Run each cell in order. All required packages will be installed automatically using `pip` commands embedded in the notebook.

#### ✅ Option 2: Jupyter Notebook (Local)

1. Make sure you have Python 3.x installed.
2. Launch Jupyter Notebook in the directory containing the notebook.
3. Run the notebook cells. The required packages will be installed via `!pip install` commands included in the notebook.

## 🔗 Download Pretrained Model

The pretrained model weights are available via external storage due to GitHub's size limitations:

👉 [Download weights from Google Drive](https://drive.google.com/file/d/1BDyfdXhv2_oRX-EJF7ShEXSok032exGv/view?usp=drive_link)

Place the downloaded file in the `models/` directory before running the code.

---

### 📦 Requirements

- Python 3.x
- Internet connection (to install packages via `pip`)
- No need for a separate `requirements.txt` file — everything is included in the notebook.

---

✅ **Tip:** For a smoother experience, it's recommended to run the notebook in Google Colab Pro if your project requires more memory or GPU acceleration.

### 📄 Reference

A. Morales-Martínez, E. Garduño, J. M. Carazo, C. O. Sorzano Sánchez, and J. L. Vilas,  
“*Membrane and vesicle structure detection in cryo-electron tomography based on deep learning*,” unpublished manuscript, in preparation, 2025.

