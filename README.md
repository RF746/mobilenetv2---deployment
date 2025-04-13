
# 🧠 MobileNetV2 Edge Deployment Optimization – PM & Engineering Hybrid Workflow

This project simulates a full-cycle AI software delivery initiative, executed with the mindset of a Technical Project Manager operating within a hardware-aware environment. The workflow demonstrates how a model is planned, scoped, optimized, and benchmarked for edge AI use — aligning with the performance and efficiency needs of AI-centric compute platforms.

---

## 📍 Project Objective

**Deliver an optimized, portable AI model pipeline** that simulates deployment on edge/embedded hardware (like custom chips or RISC-V-based systems), balancing inference speed, file size, and runtime compatibility.

---

## 🔧 Project Management Methodology

- **Approach:** Agile-inspired phase structure
- **Planning:** Phased backlog (PyTorch → ONNX → Quantized ONNX)
- **Execution:** Weekly milestones & sprint-style review
- **Tracking Tools:** Task board matrix (included below)
- **PM Mindset:** Scope → Optimize → Validate → Report

---

## 🛠️ Stack + Tooling

| Category | Tool |
|---------|------|
| Modeling & Inference | PyTorch, ONNX |
| Optimization | ONNX Runtime Quantization |
| Measurement & Analysis | Python, Matplotlib, `time`, file size profiling |
| Delivery Environment | Google Colab |
| Docs & Visuals | Markdown, Matplotlib, Google Workspace |

---

## 🚦 Key Deliverables

- ✅ Model successfully loaded, converted, and tested across formats
- ✅ Quantized model reduced by ~72% with sub-100ms inference time
- ✅ ONNX Runtime used to validate quantized format under CPU-only constraints
- ✅ Runtime errors diagnosed and resolved (ConvInteger → fallback quantization)
- ✅ Bar charts generated to compare size and speed across formats
- ✅ README + Visuals delivered as stakeholder-facing final report

---

## 🔍 Technical Results

| Metric                     | Value             |
|---------------------------|-------------------|
| Original ONNX Model Size  | ~13 MB            |
| Quantized Model Size      | **3.69 MB**       |
| Inference Time (Quantized)| **0.0715 sec**    |
| Format Compatibility      | ✅ ONNX Runtime |


### 📊 Visual Insights

![Model Size](model_size_comparison.png)  
*Model size reduction across formats*

![Inference Time](inference_time_comparison.png)  
*Latency improvement for quantized ONNX*

---

## 🗂️ Task Tracking Board (Sprint Simulation)

| Task | Description | Status | Priority |
|------|-------------|--------|----------|
| Load pretrained model | Load MobileNetV2 in PyTorch and verify inference | ✅ Done | High |
| Export model to ONNX | Convert model for cross-platform use | ✅ Done | High |
| Run ONNX inference | Validate ONNX output | ✅ Done | High |
| Quantize ONNX model | Optimize model for edge hardware | ✅ Done | High |
| Resolve ONNX Runtime errors | Adjust for unsupported Conv ops | ✅ Done | High |
| Benchmark & visualize | Generate metrics and performance charts | ✅ Done | Medium |
| Write documentation | Create README + visual summaries | ✅ Done | High |
| Simulate PM workflow | Structure execution like a product sprint | ✅ Done | Medium |

---

## 🔑 Key Skills Demonstrated

- 🧠 **AI Optimization & Quantization**
- 📋 **Agile Sprint Planning**
- ⚙️ **Problem Solving (Runtime Debugging)**
- 🧾 **Stakeholder-Ready Documentation**
- 📈 **Benchmark Analysis & Reporting**
- 🛠️ **Tool Integration (PyTorch, ONNX, Matplotlib, Colab)**

---

## 🎓 About the Author

**Ryan Faxigue**  
Software Engineer | AI Product Builder | Embedded Systems & PM Advocate

I build scalable AI solutions and manage technical initiatives from planning to deployment — always balancing user impact with real-world hardware performance needs.

📫 Connect:  
- [LinkedIn](https://www.linkedin.com/in/ryanfaxigue)  
- [GitHub](https://github.com/ryanfaxigue)

---

## 🔭 Future Expansion

- TFLite Conversion for Mobile
- Raspberry Pi Inference Benchmarking
- Streamlit Dashboard for Visual QA
