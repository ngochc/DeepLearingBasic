# Deep Learning Basic - MNIST Classification Demo

This repository contains a comprehensive Jupyter notebook demonstrating simple deep learning for image classification using the MNIST dataset.

## 🚀 Quick Start

### **Option 1: Use the Startup Script (Recommended)**
```bash
./run_notebook.sh
```

### **Option 2: Manual Setup**
```bash
# Install dependencies
pip install -r requirements.txt

# Start JupyterLab
python -m jupyter lab mnist_deep_learning_demo.ipynb

# Or start classic Jupyter Notebook
python -m jupyter notebook mnist_deep_learning_demo.ipynb
```

## Overview

The notebook `mnist_deep_learning_demo.ipynb` demonstrates:

- **Dataset**: MNIST handwritten digit classification (0-9)
- **Model**: Simple 3-layer neural network
- **Framework**: PyTorch with Mac MPS support
- **Features**: Comprehensive analysis and visualizations

## ✅ **All Requested Features Implemented:**

1. **✅ MNIST Dataset**: Complete loading, exploration, and preprocessing
2. **✅ Simple Neural Network**: 3-layer fully connected architecture  
3. **✅ Loss Function**: Cross-entropy loss with detailed analysis
4. **✅ Feature Maps**: Detailed visualization of activations at each layer
5. **✅ Loss Landscape**: 3D visualization of optimization surface + PCA-based 3D scatter plot
6. **✅ 3D Data Visualization**: PCA and t-SNE for dimensionality reduction  
7. **✅ Training/Validation Loss**: Comprehensive curves and analysis
8. **✅ Complete Metrics**: Accuracy, precision, recall, F1-score with visualizations
9. **✅ Educational Content**: Deep explanations and insights
10. **✅ Mac MPS Support**: Metal Performance Shaders for Apple Silicon

## 🎯 **Advanced Visualizations:**

- **Feature Map Analysis**: See what each layer learns
- **Loss Landscape Visualization**: Traditional 3D surface plots + NEW PCA-based 3D scatter visualization
- **3D Data Space Plots**: Compare raw data vs learned features using PCA
- **Comprehensive Metrics Dashboard**: 12-panel analysis including ROC curves
- **Wrong Predictions Analysis**: Visual analysis of model failures with confidence scores
- **Overfitting Analysis**: Monitor training dynamics
- **Confidence Distribution**: Understand model certainty
- **Per-class Performance**: Detailed breakdown by digit

## 📋 Requirements

- Python 3.7+
- PyTorch 1.9+ (with MPS support for Mac)
- All dependencies listed in `requirements.txt`

## 🔧 Troubleshooting

### **If `jupyter` command is not found:**
Use the Python module approach:
```bash
python -m jupyter lab mnist_deep_learning_demo.ipynb
```

### **If packages are missing:**
```bash
pip install -r requirements.txt
```

### **To validate notebook without running:**
```bash
python -c "
import json
with open('mnist_deep_learning_demo.ipynb', 'r') as f:
    nb = json.load(f)
print(f'Notebook has {len(nb[\"cells\"])} cells and is valid')
"
```

## 📊 Expected Results

The notebook will:
- Automatically detect and use Mac MPS, CUDA, or CPU
- Download and load the MNIST dataset  
- Train a simple neural network for 10 epochs
- Achieve approximately 95-98% accuracy on the test set
- Generate 20+ comprehensive visualizations and analyses
- Provide detailed educational insights

## 🧠 Learning Objectives

This demo helps understand:
- Basic neural network architecture
- Training process and optimization
- Feature learning and visualization
- Loss landscape analysis
- Model evaluation metrics  
- Data visualization techniques
- Overfitting and generalization concepts

## 🎓 Educational Features

- **Step-by-step explanations** of deep learning concepts
- **Interactive visualizations** of network internals
- **Comprehensive metrics analysis** with multiple evaluation methods
- **3D data space visualization** showing data transformation
- **Loss landscape exploration** revealing optimization characteristics

## 📁 Project Structure

```
DeepLearingBasic/
├── mnist_deep_learning_demo.ipynb  # Main notebook (38 cells)
├── requirements.txt                # Python dependencies
├── run_notebook.sh                # Startup script
└── README.md                      # This file
```

## 🚀 Next Steps

After completing this basic demo, you can explore:
- Convolutional Neural Networks (CNNs)
- More complex architectures  
- Advanced optimization techniques
- Data augmentation strategies
- Transfer learning approaches
- Other datasets (CIFAR-10, ImageNet)

## 💡 Tips

- **Use JupyterLab** for the best experience with interactive widgets
- **Run cells sequentially** to avoid dependency issues
- **Adjust epochs** (currently 10) based on your time constraints
- **Experiment with hyperparameters** to see their effects
- **Try different visualizations** by modifying the code

---

🎉 **Ready to dive into deep learning!** Start with `./run_notebook.sh` and explore the fascinating world of neural networks.