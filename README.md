# Handwriting Digit Recognition 📝🔢

## About  
This project implements a **Handwriting Digit Recognition system** using the MNIST dataset. The model is built with deep learning techniques to automatically classify handwritten digits (0–9). Such systems are widely used in real-world applications like postal code recognition, bank cheque verification, and form digitization.

---

## Features  
- 📊 Preprocessing of MNIST dataset (grayscale images of digits).  
- 🧠 Deep Learning model built using **TensorFlow/Keras**.  
- 📈 Model evaluation with accuracy, loss, and visualization of predictions.  
- 🎨 Visualization of training performance (loss/accuracy curves).  
- 🚀 Ready for deployment or integration with GUI/API in the future.  

---

## Tech Stack  
- **Programming Language**: Python  
- **Libraries & Frameworks**:  
  - NumPy, Pandas, Matplotlib, Seaborn  
  - TensorFlow / Keras (for building ANN/CNN models)  
  - Scikit-learn (for evaluation metrics)  
- **Environment**: Jupyter Notebook  

---

## Installation  
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/handwriting-digit-recognition.git
   cd handwriting-digit-recognition

2. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate    # On Linux/Mac
    venv\Scripts\activate       # On Windows

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt

## Usage
1. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook "Hand writing digit recognition .ipynb"

2. **Run all cells to:**

- Train the model.
- Evaluate performance.
- Visualize predictions.

## Demo

**Here’s an example of model predictions:**
- Input Digit Image → Predicted Output Label
- Visualizations of loss and accuracy curves during training.

## Project Structure
```graphql
📂 handwriting-digit-recognition
 ┣ 📜 Hand writing digit recognition .ipynb   # Main notebook
 ┣ 📜 requirements.txt                        # Dependencies
 ┣ 📜 README.md                               # Project documentation
 ┣ 📂 data/                                   # Dataset (MNIST - auto downloaded by Keras)
 ┣ 📂 models/                                 # Saved trained models (future scope)
 ┣ 📂 results/                                # Plots, evaluation metrics, and predictions
 ┗ 📂 demo/                                   # Screenshots / GIFs for README showcase
```

## Configuration

- Dataset: MNIST (automatically fetched using Keras API).
- Model Architecture: Configurable (MLP / CNN).
- Hyperparameters: Batch size, learning rate, number of epochs can be adjusted in the notebook.
- Outputs: Model accuracy, confusion matrix, sample predictions, and saved model files.

## Contributing

**Contributions are welcome! 🎉**
**To contribute:**

- Fork the repository.
- Create a new branch (feature-branch).
- Commit your changes.
- Open a pull request.

## Testing

- ✅ Training/Validation split for model evaluation.
- ✅ Accuracy and loss visualizations.
- ✅ Test set predictions and confusion matrix.
- ✅ Can extend to test with custom handwritten digit images.

## Authors / Credits

👩‍💻 Shrunkhala S

Master’s in Business Intelligence & Analytics

[LinkedIn](https://www.linkedin.com/in/shrunkhalasandeepsisodia/)

## Future Scope

- 🔮 Build a GUI/Web App for real-time digit recognition.
- 📱 Deploy as a mobile app using TensorFlow Lite.
- ☁️ Integrate with cloud platforms (AWS, GCP, Azure) for scalable inference.
- 🖼️ Extend model to recognize alphabets or handwritten words.
