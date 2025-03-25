# **Posterior Probability: A Simple Guide**  

### **What is Posterior Probability?**  
Posterior probability is the **updated probability** of an event occurring after considering new information. It is calculated using **Bayes’ Theorem**:  

\[
P(A|B) = \frac{P(A) \times P(B|A)}{P(B)}
\]  

Where:  
- **P(A|B)** = Probability of event A given event B (posterior probability)  
- **P(A)** = Prior probability of event A  
- **P(B)** = Probability of event B  
- **P(B|A)** = Probability of event B given event A  

### **Example: Finding the Probability of an Oak Tree**  
A forest has:  
- **20% Oak trees** (P(Oak) = 0.2)  
- **80% Maple trees**  
- **90% of Oak trees** are healthy (P(Healthy|Oak) = 0.9)  
- **50% of Maple trees** are healthy  
- Probability of selecting a **healthy tree**:  
  \[
  P(Healthy) = (0.2 \times 0.9) + (0.8 \times 0.5) = 0.58
  \]  

To find the probability that a **healthy tree** is an **Oak**, we use:  

\[
P(Oak|Healthy) = \frac{P(Oak) \times P(Healthy|Oak)}{P(Healthy)}
\]  
\[
= \frac{0.2 \times 0.9}{0.58} = 0.3103
\]  

Thus, **if a tree is healthy, the probability that it’s an Oak is ~31%**.  

### **Why Use Posterior Probability?**  
Posterior probability helps update **previous beliefs** when new information becomes available.  

🔹 **Example:** Initially, the probability of a tree being Oak was **20%** (prior probability). After knowing the tree is healthy, the probability increases to **31%** (posterior probability).  

### **Applications of Posterior Probability**  
Used in various fields to refine predictions:  
- **Medicine** (predicting disease probability after a test result)  
- **Finance** (adjusting stock market predictions)  
- **Weather Forecasting** (updating storm probability after satellite images)  
- **Economics** (adjusting market trends based on new data)  

### **Conclusion**  
Posterior probability allows us to make **more informed decisions** by continuously updating our beliefs based on **new evidence**.