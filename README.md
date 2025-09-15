# 🧠 CIFAR-10 Binary Classification with CNN  

This project applies **Convolutional Neural Networks (CNNs)** to the **CIFAR-10 dataset**, reformulated as a **binary classification problem**:  

- **Animals**: bird, cat, deer, dog, frog, horse  
- **Vehicles**: airplane, automobile, ship, truck  

The goal was to explore CNN architectures and compare their performance while addressing overfitting with techniques like **dropout, batch normalization, and regularization**.  

---

## 📂 Repository Contents  
- **`CNN_Model.ipynb`** → Jupyter Notebook with CNN implementation, training, and evaluation.  
- **`a_detailed_report.pdf`** → Full report including dataset description, experiments, results (KNN, Logistic Regression, CNN), and analysis.  

---

## 🏗 CNN Models Implemented  
- **Model 1: Basic CNN** – Single conv layer, simple architecture.  
- **Model 2: CNN with Dropout** – Regularized, stable performance, best accuracy.  
- **Model 3: CNN with Batch Normalization** – Improved training stability and generalization.  

📊 **Results:** CNN achieved **92–94% accuracy**, outperforming traditional models.  

---

## 📑 Report  
For a complete description of dataset preprocessing, experimental setups, results comparison (KNN, Logistic Regression, CNN), and future work, check the report:  

📄 [a_detailed_report.pdf](./a_detailed_report.pdf)  

---

## 🚀 Future Directions  
- Try **transfer learning** with pretrained models (ResNet, EfficientNet).  
- Combine CNN feature extraction with classical ML (e.g., SVM).  
- Add **Grad-CAM visualizations** for interpretability.  
