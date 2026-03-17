# 📘 Week 3 – Learnings

## 🔹 1. Embeddings Implementation

- Used sentence-transformers model (`all-MiniLM-L6-v2`)
- Converted text into vector embeddings

### Output Observed:
- Shape of embeddings → (5, 384)
- Each word converted into 384-dimensional vector

### Observation:
- cat vs kitten → high similarity (~0.9+)
- car vs automobile → high similarity
- cat vs car → low similarity

### Learning:
Embeddings capture semantic meaning, not just words.

---

## 🔹 2. Cosine Similarity

- Implemented cosine similarity using NumPy

### Output Observed:
- Values ranged between 0 and 1
- Higher value → more similar

### Example Results:
- cat vs kitten → HIGH  
- cat vs dog → MEDIUM  
- cat vs car → LOW  

### Learning:
Cosine similarity helps measure semantic closeness.

---

## 🔹 3. Semantic Search

- Built a semantic search system using embeddings

### Steps Performed:
1. Embedded all documents  
2. Embedded query  
3. Calculated similarity  
4. Sorted top results  

### Output Observed:

Query: "how to deploy an application"  
→ Top result: Docker-related document  

Query: "animal that lives at home"  
→ Top result: pets-related document  

Query: "building an API in Python"  
→ Top result: FastAPI document  

### Learning:
Semantic search works based on meaning, not exact words.

---

## 🔹 4. TF-IDF Search

- Implemented keyword-based search using TF-IDF

### Output Observed:
- Returns results only when keywords match
- Less accurate for natural language queries

### Example:
Query: "deploy application"  
→ Sometimes misses relevant documents  

### Learning:
TF-IDF is fast but lacks semantic understanding.

---

## 🔹 5. Topic Modeling (LDA)

- Applied LDA to extract topics from documents

### Output Observed:
Discovered Topics:
- Sports → (team, match, player)  
- Finance → (bank, inflation, market)  
- Health → (doctor, hospital, vaccine)  

### Additional Output:
- Each document assigned a topic with confidence score

### Learning:
LDA automatically groups documents into meaningful categories.

---

## 🔹 6. Comparison of Methods

### Output Comparison:

Query: "economic crisis and money problems"

- Semantic Search → Correct finance-related results  
- TF-IDF → Less accurate  
- LDA → Classified into Finance topic  

### Learning:
- Embeddings → best for meaning  
- TF-IDF → best for exact match  
- LDA → best for grouping  

---

## 🔹 7. Overall Learning

- Text can be converted into numerical vectors  
- Similar meaning → similar vectors  
- Semantic search is more powerful than keyword search  
- Combining multiple methods improves performance  

---

## 📌 Conclusion

- Successfully implemented embeddings, similarity, semantic search, TF-IDF, and topic modeling  
- Observed real outputs and compared results  
- Gained practical understanding of NLP techniques  