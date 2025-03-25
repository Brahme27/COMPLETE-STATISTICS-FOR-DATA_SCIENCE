### **Why Use Posterior Probability? (Detailed Explanation)**  

#### **Understanding the Concept**  
Posterior probability **updates our belief** about an event after learning new information. It helps us refine our predictions instead of relying only on initial assumptions.  

Let’s break it down with the tree example.  

---

### **Step 1: Initial Probability (Prior Probability)**
Before we know anything about a tree’s health, we only know that:  
- **20% of the trees** in the forest are Oak (**P(Oak) = 0.2**)  
- **80% of the trees** are Maple (**P(Maple) = 0.8**)  

So, if you randomly pick a tree **without any other information**, the probability that it’s an Oak tree is **20% (or 0.2)**.  
This is called the **prior probability** because it is based on initial knowledge **before** considering any extra details.

---

### **Step 2: Adding New Information (Tree is Healthy)**  
Now, suppose you find out that the tree you selected is **healthy**.  

We also know:  
- **90% of Oak trees** are healthy (**P(Healthy|Oak) = 0.9**)  
- **50% of Maple trees** are healthy (**P(Healthy|Maple) = 0.5**)  

But how does this information affect the probability of the tree being Oak?  

We now need to consider:  
- The total number of **healthy trees** in the entire forest.  
- How many of those healthy trees are actually Oak.  

---

### **Step 3: Calculating the Probability of a Healthy Tree**  
We calculate the probability of randomly picking a healthy tree (**P(Healthy)**) by adding up all the healthy trees from both categories (Oak and Maple):  

\[
P(Healthy) = (P(Oak) \times P(Healthy|Oak)) + (P(Maple) \times P(Healthy|Maple))
\]

Substituting values:  

\[
P(Healthy) = (0.2 \times 0.9) + (0.8 \times 0.5)
\]

\[
= 0.18 + 0.40 = 0.58
\]

So, **58% of all trees in the forest are healthy**.

---

### **Step 4: Updating the Probability (Posterior Probability)**  
Now, we want to find out:  
**Given that the tree is healthy, what is the probability that it is an Oak tree?**  

We use **Bayes' Theorem**:  

\[
P(Oak|Healthy) = \frac{P(Oak) \times P(Healthy|Oak)}{P(Healthy)}
\]

\[
= \frac{(0.2 \times 0.9)}{0.58}
\]

\[
= \frac{0.18}{0.58} = 0.3103
\]

So, after knowing that the tree is healthy, the probability that it’s **an Oak tree increases from 20% to 31%**.

---

### **Step 5: Why Did the Probability Change?**  
Originally, we only knew the overall percentage of Oak trees (**20%**), so our best guess was that any tree we picked had a 20% chance of being Oak.  

But after learning that the tree is **healthy**, we used that **extra information** to refine our estimate. Since Oak trees have a higher chance of being healthy (**90%**) compared to Maple trees (**50%**), it becomes more likely that the healthy tree we picked is **Oak** rather than Maple.  

So, the probability of the tree being Oak **increased from 20% to 31%** after considering this new evidence.

---

### **Key Takeaway**  
- **Prior Probability** → The initial probability before any extra information (e.g., 20% of all trees are Oak).  
- **New Information** → The tree is healthy.  
- **Posterior Probability** → The updated probability after considering new information (31% chance the tree is Oak).  

**Posterior probability helps us make better predictions by updating our beliefs when we learn new facts.**