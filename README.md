# Brain Tumor Detection Using AI/ML/DL

This project is an AI-driven solution for brain tumor detection using deep learning models. The implementation utilizes TensorFlow, Hugging Face models, and various preprocessing techniques.

## Features
- Data preprocessing and verification
- Model training and inference
- Uses `BERT` for NLP-based medical data processing
- Integration with Hugging Face models

## Project Structure
```
Round/
│── data/                 # Contains datasets
│── scripts/              # Contains Python scripts
│   │── inference.py      # Model inference script
│   │── preprocess_data.py # Data preprocessing script
│   │── train.py          # Model training script
│   │── verify_data.py    # Data verification script
│── slm book/             # Additional references
│── main.py               # Main entry script
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/brain-tumor-detection.git
   cd brain-tumor-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Ensure TensorFlow is installed and working:
   ```sh
   python -c "import tensorflow as tf; print(tf.__version__)"
   ```

## Usage
Run inference:
```sh
python scripts/inference.py
```
Expected output:
```
Q: What does Hugging Face provide?
A: open-source NLP models
```

## Demo Screenshot
![Demo Output](demo.png)

## Author
Sutham

## License
MIT License
