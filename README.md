# ✍️ Handwriting Detection using ANN 🧠

This project demonstrates how to build an **Artificial Neural Network (ANN)** to detect handwritten digits using the popular **MNIST dataset**. It covers preprocessing, model training, evaluation, and visualization of predictions.

## 📁 Project Structure

- `handwriting detection.ipynb` – Jupyter Notebook with all the steps from data loading to model evaluation.
- `README.md` – Project overview and usage instructions.
- `model.h5` *(optional)* – Saved trained ANN model.

## 🧠 Model Overview

A simple feedforward ANN was built using **Keras** (TensorFlow backend) to classify digits (0–9) from handwritten images.

- **Input Layer:** 784 neurons (28x28 pixels flattened)
- **Hidden Layers:** 1 or more Dense layers with ReLU activation
- **Output Layer:** 10 neurons (Softmax activation)
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam

## ⚙️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/prateek-g-bit/handwriting-detection-ann.git
   cd handwriting-detection-ann
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook
   ```

4. Open and run `handwriting detection.ipynb`.

## 📊 Dataset

The model uses the **MNIST** dataset:
- 60,000 training images
- 10,000 test images
- 28x28 grayscale handwritten digits

This dataset is automatically loaded via Keras.

## 📈 Results

The model achieves high accuracy (~97-98%) on the test set. You can visualize sample predictions in the notebook output.

## ✅ Future Enhancements

- Use Convolutional Neural Networks (CNNs) for improved accuracy
- Add real-time digit drawing and prediction (e.g., using Tkinter or Streamlit)
- Export the model to ONNX or TFLite for deployment

## 📌 License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to fork or contribute! 😊
