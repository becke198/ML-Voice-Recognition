# Yes/No Speech Classifier (TFLite)

This project demonstrates a simple **keyword spotting** demo using a TensorFlow Lite model. It detects whether the spoken word in an uploaded `.wav` file is **"yes"** or **"no"** using on-device inference logic.

## 🔍 Features

- Loads and runs a `.tflite` model
- Accepts user-uploaded WAV files
- Preprocesses and feeds audio data to the model
- Returns prediction: "yes" or "no"

## 📁 Files

| File | Purpose |
|------|---------|
| `AI_Project_Yes_No_Recognition.ipynb` | Core Colab notebook |
| `model.tflite` | Pretrained TFLite model |
| `example_audio_yes.wav` / `no.wav` | Sample inputs |
| `requirements.txt` | Dependencies (TensorFlow, NumPy, SciPy) |

## 🧪 Demo
[Link to Colab](https://colab.research.google.com/drive/1vnOZg-cGDHnm5m8dj286EXZu7dwqrXlW?usp=sharing)
<img src="assets/demo.gif" width="600" alt="demo" />

## 🚀 Getting Started

```bash
pip install tensorflow scipy numpy
