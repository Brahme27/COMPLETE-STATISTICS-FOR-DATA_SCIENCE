# **Set Operations: Simplified Guide**  

## **1. What is a Set?**  
A **set** is a **collection of unique items**.  
- Example: **A = {1, 2, 3}**  

---

## **2. Common Set Operations**  

### **(i) Union (A ∪ B) – Items in Either A or B**  
Combines elements from both sets without duplicates.  

**Examples:**  
- {1, 2, 3} ∪ {4, 5, 6} = **{1, 2, 3, 4, 5, 6}**  
- {1, 2, 3} ∪ {3, 4} = **{1, 2, 3, 4}**  

---

### **(ii) Intersection (A ∩ B) – Items in Both A and B**  
Finds common elements between sets.  

**Examples:**  
- {1, 2, 3} ∩ {4, 5, 6} = **∅ (empty set, no common items)**  
- {1, 2, 3} ∩ {3, 4} = **{3}**  

---

### **(iii) Complement (A' or Ac) – Items Not in A**  
Elements in the universal set (U) but not in A.  

**Examples (if U = {1, 2, 3, 4, 5, 6}):**  
- A = {1, 2} → Ac = **{3, 4, 5, 6}**  
- A = {1, 2, 3} → Ac = **{4, 5, 6}**  

---

### **(iv) Difference (A – B) – Items in A, but Not in B**  
Removes elements of B from A.  

**Examples:**  
- {1, 2, 3} – {2, 3, 4} = **{1}**  
- {1, 2, 3} – {4, 5} = **{1, 2, 3}**  

---

### **(v) Symmetric Difference (A Δ B) – Items in A or B, but Not in Both**  
Keeps elements unique to each set and removes common ones.  

**Examples:**  
- {1, 2, 3} Δ {2, 3, 4} = **{1, 4}**  
- {1, 2, 3} Δ {4, 5} = **{1, 2, 3, 4, 5}**  

---

### **(vi) Cartesian Product (A × B) – Ordered Pairs from Both Sets**  
Forms pairs (a, b) with elements from A and B.  

**Examples:**  
- If **A = {H, T}** and **B = {1, 2, 3}**  
  - A × B = **{(H,1), (H,2), (H,3), (T,1), (T,2), (T,3)}**  

---

## **3. Summary**  
- **Union (A ∪ B):** Combines both sets.  
- **Intersection (A ∩ B):** Finds common elements.  
- **Complement (A’ or Ac):** Elements not in A.  
- **Difference (A – B):** Items in A but not in B.  
- **Symmetric Difference (A Δ B):** Unique elements in each set.  
- **Cartesian Product (A × B):** Ordered pairs from both sets.  