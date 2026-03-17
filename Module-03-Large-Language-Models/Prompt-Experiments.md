# 🧪 Week 3 – Prompt Experiments

## 🔹 1. Embedding Experiment

### Input:
["cat", "kitten", "dog", "car", "automobile"]

### Output:
- Generated embeddings of shape (5, 384)

### Observation:
- cat ≈ kitten → high similarity  
- car ≈ automobile → high similarity  

---

## 🔹 2. Similarity Experiment

### Output:
- cat vs kitten → ~0.9+  
- cat vs dog → ~0.6  
- cat vs car → ~0.2  

### Observation:
- Similar words → higher score  
- Unrelated words → lower score  

---

## 🔹 3. Semantic Search Experiment

### Query 1:
"how to deploy an application"  
→ Output: Docker-related document  

### Query 2:
"animal that lives at home"  
→ Output: Pets-related document  

### Query 3:
"building an API in Python"  
→ Output: FastAPI-related document  

### Observation:
- Works even without exact keyword match  

---

## 🔹 4. TF-IDF Experiment

### Output:
- Works well for exact keyword matches  
- Fails for synonym-based queries  

### Observation:
- Keyword-based approach is limited  

---

## 🔹 5. Topic Modeling Experiment

### Output:
- Topic 1 → Sports  
- Topic 2 → Finance  
- Topic 3 → Health  

### Observation:
- Automatically groups similar documents  

---

## 🔹 6. Final Comparison

### Query:
"economic crisis and money problems"

### Output:
- Semantic Search → Best result  
- TF-IDF → Moderate result  
- LDA → Finance topic  

### Observation:
- Semantic search is most effective  

---

## 📌 Conclusion

- Compared multiple NLP techniques  
- Verified outputs practically  
- Understood strengths and limitations of each method  