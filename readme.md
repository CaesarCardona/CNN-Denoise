# 🧠 CNN Denoise

## 🧩 Requirements
- **Python 3** (to create a virtual environment and install dependencies from `requirements.txt`)

## 🚀 Execution

### 🌀 Add Noise to Your Image Dataset
```bash
python3 add-noise.py
```

## 🏋️‍♂️ Train the network
```bash
python3 model-denoise.py
```

MSE is shown in terminal for each Epoch and images are saved in 'predicted' folder.

## 📊 To evaluate using trained network:
```bash
python3 evaluate.py
```
