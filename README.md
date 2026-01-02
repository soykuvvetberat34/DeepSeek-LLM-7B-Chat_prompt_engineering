# DeepSeek-LLM-7B-Chat Fine-Tuning for Turkish Legal Text Generation

This repository presents fine-tuning and evaluation results of the
**DeepSeek-LLM-7B-Chat** model on a **Turkish legal domain dataset**.

The task focuses on generating legally consistent decision texts
based on structured court information.

---

## 🔍 Model Information

- Base Model: **DeepSeek-LLM-7B-Chat**
- Language: **Turkish**
- Domain: **Legal / Court Decisions**
- Task Type: **Text Generation / Legal Decision Continuation**

---

## 📊 Dataset Statistics

| Split | Samples | Tokens |
|-----|--------|--------|
| Train | 80 | 40,960 |
| Test  | 20 | 10,240 |
| Total | 100 | 51,200 |

---

## ⚙️ Training Configuration

- Epochs: 2
- Batch Size: 1
- Learning Rate: 1e-4
- Training Time: 23.60 seconds
- Training Loss: **0.9726**

---

## 🧪 Test Metrics

| Metric | Value |
|------|-------|
| Accuracy | 0.4500 |
| Precision | 0.2025 |
| Recall | 0.4500 |
| F1 Score | 0.2793 |
| R2-like Score | 0.6820 |
| Avg. Confidence | 0.9140 |

---

## 📝 Qualitative Evaluation

- Answer Quality: **100%**
- Meaningful Responses: **3 / 3**
- Avg. Tokens per Answer: **99.3**

---

## ⚠️ Disclaimer

This model is intended **only for research and experimental purposes**  
and must **not** be used as a legal advisory system.
