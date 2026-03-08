 # 🧠 Activity: Comparing Prompting Techniques

---

## 📌 Task
Find the **largest number in a list of numbers**.

---

## 🔹 1. Basic Prompt

A **basic prompt** is simple but may be unclear or less structured.

### Prompt
```
Find the largest number in this list: 5, 12, 3, 21, 8.
```

### Typical Response
```
The largest number in the list is 21.
```

### 🔍 Observation
- Short answer  
- No explanation  
- Correct but limited depth  

---

## 🔹 2. Zero-Shot Prompt

**Zero-shot prompting** means **no examples are given**, but the instruction is clearer.

### Prompt
```
You are a helpful assistant. Identify the largest number from the following list of numbers: 5, 12, 3, 21, 8. Provide the final answer.
```

### Response
```
The numbers are 5, 12, 3, 21, and 8.
Among these numbers, 21 is the largest.

Final Answer: 21
```

### 🔍 Observation
- Slightly clearer explanation  
- Still simple reasoning  
- Works well for straightforward tasks  

---

## 🔹 3. Few-Shot Prompt

**Few-shot prompting** provides examples so the model understands the pattern.

### Prompt
```
Find the largest number in the list.

Example 1:
Input: 3, 7, 2, 9
Output: The largest number is 9.

Example 2:
Input: 10, 4, 6, 15
Output: The largest number is 15.

Now solve this:
Input: 5, 12, 3, 21, 8
Output:
```

### Response
```
The largest number is 21.
```

### 🔍 Observation
- Model follows pattern from examples  
- More reliable for complex tasks  
- Improves accuracy  

---

## 🔹 4. Chain-of-Thought Prompt

**Chain-of-Thought prompting** encourages **step-by-step reasoning**.

### Prompt
```
Find the largest number in the list: 5, 12, 3, 21, 8.
Think step by step and explain your reasoning before giving the final answer.
```

### Response
```
Step 1: The numbers are 5, 12, 3, 21, and 8.
Step 2: Compare the numbers to find the greatest value.
Step 3: 21 is greater than 5, 12, 3, and 8.

Final Answer: 21
```

### 🔍 Observation
- Clear reasoning  
- More detailed  
- Useful for complex problems like math or logic  

---

# 📊 Evaluation of Prompting Techniques

We will evaluate using the **RAA Method (Relevance, Accuracy, Analysis Depth).**

### 🔹 Basic Prompt
- **Relevance:** Medium  
- **Accuracy:** High  
- **Depth:** Low  

### 🔹 Zero-Shot Prompt
- **Relevance:** High  
- **Accuracy:** High  
- **Depth:** Medium  

### 🔹 Few-Shot Prompt
- **Relevance:** High  
- **Accuracy:** Very High  
- **Depth:** Medium  

### 🔹 Chain-of-Thought Prompt
- **Relevance:** Very High  
- **Accuracy:** Very High  
- **Depth:** High  

---

# 🔎 Analysis

### 🔹 Basic Prompt
- Works for simple tasks  
- Minimal explanation  

### 🔹 Zero-Shot Prompt
- Better structured  
- Clear instruction improves response quality  

### 🔹 Few-Shot Prompt
- Examples guide the model  
- Reduces misunderstanding  

### 🔹 Chain-of-Thought Prompt
- Best for reasoning tasks  
- Shows step-by-step logic  

---

# 🏁 Conclusion

Different prompting techniques significantly affect AI responses.

- **Basic prompts** produce quick but shallow answers.  
- **Zero-shot prompts** improve clarity.  
- **Few-shot prompts** improve accuracy using examples.  
- **Chain-of-Thought prompts** produce the most detailed and explainable results.

Thus, **Chain-of-Thought prompting generally gives the most comprehensive responses**, especially for reasoning-based tasks.
