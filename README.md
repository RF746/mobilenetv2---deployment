
# 🔍 MobileNetV2 Inference & Quantization Pipeline

This project demonstrates how to load a pretrained MobileNetV2 model using PyTorch, convert it to ONNX, apply quantization for edge deployment, and run inference across all stages — with performance comparisons. It simulates a real-world AI deployment workflow, optimized for resource-constrained environments.

---

## 📌 Overview

| Phase | Description |
|-------|-------------|
| ✅ Phase 1 | Load and run MobileNetV2 in PyTorch |
| ✅ Phase 2 | Convert PyTorch model to ONNX and test inference |
| ✅ Phase 3 | Apply dynamic quantization to reduce model size |
| ✅ Phase 4 | Run quantized model using ONNX Runtime and compare performance |

---

## 🧠 Why This Matters

This project replicates the type of work done in AI-focused hardware companies (e.g., Tenstorrent), where performance, portability, and compatibility are crucial. It demonstrates:

- Model optimization for edge devices
- ONNX export for hardware interoperability
- Quantization to reduce size and improve inference speed

---

## 🛠️ Tech Stack

- **Python 3**
- **PyTorch**
- **Torchvision**
- **ONNX**
- **ONNX Runtime**
- **Google Colab (CPU)**

---

## 🖼️ Sample Input

A sample image of a Labrador Retriever is passed through the model. The same image is tested across all phases to compare performance and label consistency.

---

## 📊 Results

| Metric                     | Value             |
|---------------------------|-------------------|
| Original ONNX Model Size  | ~13 MB            |
| Quantized ONNX Model Size | **3.69 MB**       |
| Inference Time (Quantized)| **0.0715 sec**    |
| Predicted Label           | **Labrador Retriever** |

---

## 📁 Files

- `mobilenetv2_inference.ipynb` — Full notebook (PyTorch → ONNX → Quantization)
- `mobilenetv2.onnx` — Standard ONNX model
- `mobilenetv2_quantized.onnx` — Quantized ONNX model

---

## 🚀 How to Run

1. Open `mobilenetv2_inference.ipynb` in [Google Colab](https://colab.research.google.com)
2. Run all cells (Runtime > Run all)
3. Optional: Replace the test image URL with your own

---

## 🙋 About the Author

**Ryan Faxigue**  
Computer Science + Applied Math | AI/Cloud Engineering  
Passionate about AI deployment, embedded systems, and building scalable, optimized solutions.

---

## 📫 Contact

Want to collaborate or connect?

- [LinkedIn](https://www.linkedin.com/in/ryan-n-faxigue-b21813229/)
- [GitHub](https://github.com/RF746)

---

## 🏁 Future Work

- Add TensorFlow Lite conversion
- Benchmark on Raspberry Pi or Jetson Nano
- Integrate with real-time camera input

---
