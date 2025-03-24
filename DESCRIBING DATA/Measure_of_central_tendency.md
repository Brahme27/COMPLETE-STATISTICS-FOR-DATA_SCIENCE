### **Measures of Central Tendency: Simplified Summary**  

#### **What is a Measure of Central Tendency?**  
A measure of central tendency is a **single value** that represents the **center** of a dataset. It helps summarize data and provides a quick understanding of typical values. The three common measures are:  
- **Mean** (Average)  
- **Median** (Middle Value)  
- **Mode** (Most Frequent Value)  

#### **Why Are Measures of Central Tendency Useful?**  
They help in decision-making by summarizing large datasets. For example, a company analyzing employee salaries can use the median to find a typical salary without being affected by extremely high salaries.  

---

## **1. Mean (Average)**
### **Mathematical Formula**  
\[
\text{Mean} = \frac{\sum X}{N}
\]
where:  
- \( X \) = individual data points  
- \( N \) = total number of data points  

### **Real-World Example**  
A teacher wants to calculate the average test score of a class. If the scores are:  
\[
80, 85, 90, 95, 100
\]  
The mean is:  
\[
\frac{80 + 85 + 90 + 95 + 100}{5} = 90
\]

### **When to Use the Mean?**  
- Best for **symmetrical data** (no extreme values).  

### **Example with an Outlier**  
If one student scores **0**, the new dataset is:  
\[
0, 80, 85, 90, 95, 100
\]  
New mean:  
\[
\frac{0 + 80 + 85 + 90 + 95 + 100}{6} = 75
\]  
The mean drops significantly because of the outlier (0), making it **misleading** in this case.  

---

## **2. Median (Middle Value)**
### **How to Find the Median?**  
1. **Sort the data in ascending order.**  
2. If **odd** number of values → middle value is the median.  
3. If **even** number of values → median is the **average of the two middle values**.  

### **Mathematical Formula**  
For a dataset with \( N \) values sorted in ascending order:  
- If \( N \) is **odd**:  
  \[
  \text{Median} = X_{\frac{N+1}{2}}
  \]
- If \( N \) is **even**:  
  \[
  \text{Median} = \frac{X_{\frac{N}{2}} + X_{\frac{N}{2} + 1}}{2}
  \]

### **Real-World Example**  
A company wants to determine a **typical salary** from these values:  
\[
30,000, 40,000, 50,000, 60,000, 70,000
\]  
Median salary = **50,000** (middle value).  

### **When to Use the Median?**  
- Best for **skewed data** or **outliers**.  

### **Example with an Outlier**  
If the highest salary is **500,000**, the new dataset is:  
\[
30,000, 40,000, 50,000, 60,000, 500,000
\]  
New mean:  
\[
\frac{30,000 + 40,000 + 50,000 + 60,000 + 500,000}{5} = 136,000
\]  
New median: **50,000** (unchanged).  
The **median is a better measure** because the outlier (500,000) **distorts the mean**.  

---

## **3. Mode (Most Frequent Value)**
### **Definition**  
The **mode** is the number that appears **most frequently** in a dataset.  

### **Mathematical Representation**  
- If \( X \) is the dataset:  
  \[
  \text{Mode} = \text{Most frequent value in } X
  \]
- A dataset can have:  
  - **No mode** (if all values are unique).  
  - **One mode** (unimodal).  
  - **Multiple modes** (bimodal, multimodal).  

### **Real-World Example**  
A clothing store tracks **most purchased T-shirt sizes**:  
\[
S, M, M, L, XL, M, L, M, S, M
\]  
Mode = **M (Medium)** because it appears the most.  

### **When to Use the Mode?**  
- Best for **categorical data** (e.g., most preferred product color).  

### **Example with an Outlier**  
In a school, most students score around **75 marks**, but one student scores **5 marks**.  
- Mode = **75** (most common score).  
- The **outlier (5)** does not affect the mode.  

---

## **Choosing the Right Measure**
| **Measure** | **Best for** | **Mathematical Formula** | **Example** |
|------------|------------|----------------------|------------|
| **Mean** | Symmetrical data, no extreme values | \( \text{Mean} = \frac{\sum X}{N} \) | Average test score in a class |
| **Median** | Skewed data, outliers present | \( \text{Median} = X_{\frac{N+1}{2}} \) (odd) or \( \frac{X_{\frac{N}{2}} + X_{\frac{N}{2} + 1}}{2} \) (even) | Typical salary in a company |
| **Mode** | Categorical data | Most frequent value | Most purchased T-shirt size |

---

### **Key Takeaways**
- **Mean** is useful for balanced datasets but is **affected by outliers**.  
- **Median** is better for skewed data or **when outliers are present**.  
- **Mode** is ideal for **categorical data** (e.g., favorite color, most sold product).  

📌 **Note**: If a dataset is perfectly **normally distributed**, the **mean, median, and mode are equal**.