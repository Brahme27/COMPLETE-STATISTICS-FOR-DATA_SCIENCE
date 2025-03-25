# **General Multiplication Rule: Simplified Guide**  

## **1. What is the General Multiplication Rule?**  
The probability of **two events (A and B) happening together** is given by:  

\[
P(A \text{ and } B) = P(A) \times P(B|A)
\]

- **P(B|A)** means "Probability of B occurring, given that A has already occurred."  
- If A and B are **independent**, then **P(B|A) = P(B)**, simplifying the rule to:

\[
P(A \text{ and } B) = P(A) \times P(B)
\]

---

## **2. Multiplication Rule for Dependent Events**  
For **dependent events**, the probability of the second event depends on the first event's outcome.  

### **Example 1: Drawing Balls from an Urn**  
- An urn has **4 red** and **3 green** balls.  
- Bob selects **2 balls without replacement**.  
- Probability of selecting **2 red balls**:  

\[
P(Both \text{ red}) = \frac{4}{7} \times \frac{3}{6} \approx 0.2249
\]

### **Example 2: Drawing Cards from a Deck**  
- A deck has **26 red** and **26 black** cards.  
- Debbie picks **2 cards without replacement**.  
- Probability of selecting **2 red cards**:  

\[
P(Both \text{ red}) = \frac{26}{52} \times \frac{25}{51} \approx 0.2451
\]

---

## **3. Multiplication Rule for Independent Events**  
For **independent events**, the second event is **not affected** by the first event.

### **Example 1: Flipping Two Coins**  
- Probability that **both coins land on heads**:  

\[
P(Both \text{ heads}) = \frac{1}{2} \times \frac{1}{2} = 0.25
\]

### **Example 2: Rolling Two Dice**  
- Probability that **both dice land on "1"**:  

\[
P(Both \text{ 1s}) = \frac{1}{6} \times \frac{1}{6} = \frac{1}{36} \approx 0.0278
\]

---

## **4. Summary**  
- **Dependent Events**: The second event depends on the first (**P(B|A) is used**).  
- **Independent Events**: The second event is not affected by the first (**P(B|A) = P(B)**).  
- **Formula:**  
  - **Dependent**: \( P(A \text{ and } B) = P(A) \times P(B|A) \)  
  - **Independent**: \( P(A \text{ and } B) = P(A) \times P(B) \)  

This rule is essential for calculating probabilities in real-world scenarios like games, finance, and risk analysis.