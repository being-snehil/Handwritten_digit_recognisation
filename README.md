# 🖊️ Handwritten Digit Recognition using TensorFlow (MNIST Dataset)

This is a deep learning project that uses **TensorFlow** and **Keras** to recognize handwritten digits (0–9) from the popular **MNIST dataset**.  
The model is a simple **neural network (Multi-Layer Perceptron)** trained to classify images of digits written by hand.

---

## 📸 What It Does ???

The model takes a 28x28 grayscale image as input and predicts which digit (0–9) it represents.

---

## 🚀 Features

- Built using **TensorFlow** and **Keras**
- Trained on the **MNIST dataset** (60,000 training images + 10,000 test images)
- Achieves high accuracy (>97%)
- Simple, clean, and beginner-friendly code

---

## 🧩 Project Structure

```
├── main.ipynb              # Jupyter Notebook (model training + evaluation)
├── dataset/                # (optional) Folder if you saved dataset manually
├── model/                  # Saved trained model (H5 or SavedModel format)
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🧠 Model Architecture

| Layer Type | Parameters | Activation | Description |
|-------------|-------------|-------------|-------------|
| Flatten | Input: (28×28) | — | Converts 2D image to 1D vector |
| Dense | 128 neurons | ReLU | Hidden layer for feature extraction |
| Dense | 10 neurons | Softmax | Output layer for classification |

---

## ⚙️ How to Run

### 1️⃣ Clone this repository:
```bash
git clone https://github.com/being-snehil/Handwritten_digit_recognisation.git
cd Handwritten_digit_recognisation
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the code:
If using a notebook:
```bash
jupyter notebook main.ipynb
```

Or if using a Python script:
```bash
python main.py
```

---

## 🧪 Results

- **Training Accuracy:** ~98.9%  
- **Validation Accuracy:** ~97.19%  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Optimizer:** Adam  

---

## 📊 Sample Inputs

| Input Image |
|--------------|
| ![digit](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png) | 

---

## 🛠️ Technologies Used

- Python 🐍  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  

---

## 📚 Dataset Information

**MNIST Dataset:**  
- 70,000 images (28x28 pixels, grayscale)  
- 10 classes (digits 0 to 9)  
- Available in TensorFlow:  
  ```python
  from tensorflow.keras.datasets import mnist
  ```

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
If you find any bug or want to improve the performance, feel free to open an issue.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**<Your Name>**  
📧 [snehilverma607@gmail.com]  
🌐 [https://github.com/being-snehil](https://github.com/being-snehil)


