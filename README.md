# topsis_for_pretrained_models_RAVNEET_KAUR_102303943
# TOPSIS on Sentence Similarity Models

## 📌 Objective
The objective of this assignment is to identify the **best pre-trained Sentence Similarity model** using the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** multi-criteria decision-making approach.

This study compares multiple sentence similarity models based on similarity accuracy and computational efficiency.

---

## 🧠 Task Chosen
**Text Sentence Similarity**  
(Roll Number ending with **3**)

---

## 🤖 Models Evaluated
The following **pre-trained sentence similarity models** were evaluated:

- SBERT  
- Universal Sentence Encoder (USE)  
- InferSent  
- SimCSE  

---

## 📊 Evaluation Criteria
The models were evaluated using the following criteria:

| Criterion | Description | Type |
|---------|------------|------|
| Cosine Similarity | Measures semantic similarity between sentences | Benefit (+) |
| Pearson Correlation | Correlation with human similarity judgments | Benefit (+) |
| Inference Time (ms) | Time taken to compute similarity | Cost (-) |
| Model Size (MB) | Memory requirement of the model | Cost (-) |

---

## ⚖ Weights and Impacts
- **Weights:** `5, 4, 3, 2`
- **Impacts:** `+ , + , - , -`

Higher importance was given to similarity accuracy metrics, followed by inference speed and model size.

---

## 📁 Input Data (`data.csv`)

| Model | Cosine Similarity | Pearson Correlation | Inference Time (ms) | Model Size (MB) |
|------|------------------|---------------------|--------------------|----------------|
| SBERT | 0.86 | 0.84 | 90 | 420 |
| USE | 0.83 | 0.82 | 110 | 500 |
| InferSent | 0.80 | 0.78 | 140 | 350 |
| SimCSE | 0.88 | 0.86 | 100 | 400 |

---

## 🔢 Methodology (TOPSIS Steps)
1. Construction of decision matrix  
2. Normalization of criteria values  
3. Application of weights  
4. Identification of ideal best and ideal worst solutions  
5. Distance calculation from ideal solutions  
6. Computation of TOPSIS score  
7. Ranking of models  

---

## 🏆 Results (`result.csv`)

| Model | TOPSIS Score | Rank |
|------|--------------|------|
| SimCSE | Highest | 1 |
| SBERT | Second Highest | 2 |
| Universal Sentence Encoder | Third | 3 |
| InferSent | Lowest | 4 |

---

## 📈 Visualization
A bar graph was plotted to visualize the **TOPSIS scores of all sentence similarity models**, clearly indicating their relative performance.

**A higher TOPSIS score represents a better-performing model.**

---

## ✅ Final Conclusion
Based on the TOPSIS analysis, **SimCSE** achieved the highest TOPSIS score and is therefore selected as the **best pre-trained sentence similarity model** among the evaluated alternatives.

---

## 🛠 Tools & Technologies Used
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib  

---

## 
