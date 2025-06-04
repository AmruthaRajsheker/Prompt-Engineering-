## **EXPERIMENT 5: Comparative Analysis of Naïve Prompting versus Basic Prompting Using ChatGPT Across Various Test Scenarios**

---

### **AIM**

To rigorously evaluate ChatGPT’s responsiveness to **naïve prompts** (broad, vague, or unstructured) versus **basic prompts** (clear, detailed, and contextually structured), by analyzing the quality, accuracy, and depth of outputs across multiple real-world scenarios. The goal is to extract actionable insights on how prompt formulation influences AI effectiveness and to recommend optimal prompting strategies for enhanced AI interaction.

---

### **ALGORITHM**

**Step 1: Define Prompt Categories**

* **Naïve Prompts**: Open-ended, ambiguous inputs lacking specific guidance or context.
* **Basic Prompts**: Well-defined, explicit instructions providing relevant context and objectives.

---

**Step 2: Identify Test Scenarios**

| Scenario No. | Use Case            | Task Description                             |
| ------------ | ------------------- | -------------------------------------------- |
| 1            | Text Summarization  | Summarize a technical article                |
| 2            | Question Answering  | Provide factual answers to direct queries    |
| 3            | Text Classification | Classify input text into predefined labels   |
| 4            | Role Playing        | Simulate a conversational agent role         |
| 5            | Code Generation     | Generate code snippets based on requirements |
| 6            | Reasoning           | Perform step-by-step logical reasoning       |

---

**Step 3: Construct Paired Prompts**

For each scenario, formulate:

* A **Naïve Prompt**: Vague or incomplete query.
* A **Basic Prompt**: Specific, detailed instruction with contextual clarity.

---

**Step 4: Execute Experiments**

* Input naïve and basic prompts separately into ChatGPT.
* Capture generated responses for comparative analysis.

---

**Step 5: Evaluate Outputs**

Assess each response on:

* **Quality**: Fluency, relevance, and engagement.
* **Accuracy**: Correctness of information or logic.
* **Depth**: Comprehensiveness and detail richness.

---

### **OUTPUT**

Below is a sample structure illustrating how prompt refinement affects output quality. (Note: ‘image’ placeholders indicate where actual ChatGPT response samples or screenshots would be embedded in a final report.)

| Scenario                | Basic Prompt Example                                                                                              | Naïve Prompt Example          | Sample Output (Basic Prompt)                                                                                                                                                                                                                                                                 | Sample Output (Naïve Prompt)                                                                        |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Text Summarization**  | "Summarize the key points of a 500-word technical article on blockchain technology focusing on security aspects." | "Summarize blockchain."       | *“Blockchain technology is a decentralized ledger system that ensures data integrity and security through cryptographic techniques. Key security features include immutability, consensus mechanisms like Proof of Work, and decentralized verification, reducing fraud and hacking risks.”* | *“Blockchain is a technology that records transactions in a digital ledger.”*                       |
| **Question Answering**  | "What are the main causes and preventive measures for Type 2 Diabetes?"                                           | "Tell me about diabetes."     | *“Type 2 Diabetes is primarily caused by insulin resistance due to obesity, poor diet, and sedentary lifestyle. Preventive measures include maintaining a healthy weight, balanced diet, regular exercise, and routine blood sugar monitoring.”*                                             | *“Diabetes is a disease where blood sugar is high.”*                                                |
| **Text Classification** | "Classify this review as positive, negative, or neutral: 'The product arrived late but works fine.'"              | "Is this review good or bad?" | *“This review is neutral. While the customer experienced a delivery delay (negative), the product itself functions properly (positive), balancing the sentiment.”*                                                                                                                           | *“The review is bad because of late delivery.”*                                                     |
| **Role Playing**        | "Act as a customer service agent handling a delayed order complaint politely."                                    | "Help with order problem."    | *“I sincerely apologize for the delay in your order. I understand how frustrating this can be. I’m looking into the issue right now and will provide an update as soon as possible. Thank you for your patience.”*                                                                           | *“Your order is late. We will check.”*                                                              |
| **Code Generation**     | "Write a Python function to compute the factorial of a number using recursion."                                   | "Factorial code."             | `python\ndef factorial(n):\n    if n == 0 or n == 1:\n        return 1\n    else:\n        return n * factorial(n-1)\n`                                                                                                                                                                      | `python\ndef fact(n):\n    res = 1\n    for i in range(1,n+1):\n        res *= i\n    return res\n` |
| **Reasoning**           | "Explain step-by-step how to solve this math problem: Find the sum of all prime numbers under 20."                | "Sum primes under 20."        | *“Step 1: Identify prime numbers less than 20: 2, 3, 5, 7, 11, 13, 17, 19. Step 2: Add these numbers: 2 + 3 + 5 + 7 + 11 + 13 + 17 + 19 = 77. Step 3: The sum is 77.”*                                                                                                                       | *“The sum of prime numbers under 20 is 77.”*                                                        |

---

### **RESULT**

* **Clarity and Structure Matter:** Basic prompts significantly outperform naïve prompts by delivering outputs with higher relevance, accuracy, and depth.
* **Quality Enhancement:** Basic prompts yield well-organized and contextually richer responses, minimizing ambiguity.
* **Scenario Sensitivity:** In creative or open-ended tasks (e.g., storytelling), naïve prompts sometimes suffice but often lack precision and consistency.
* **Reliability in Complex Tasks:** For technical, factual, or multi-step reasoning scenarios, basic prompts are indispensable to guide the AI effectively.
* **User Experience:** Clear prompts reduce the need for iterative re-queries, enhancing user productivity and satisfaction.

---

### **SUMMARY OF INSIGHTS**

* Investing time in crafting detailed, unambiguous prompts directly translates into superior AI response quality.
* Broad or naïve prompts increase the risk of irrelevant or superficial outputs, especially in professional or critical domains.
* Prompt engineering should be a strategic focus for organizations leveraging AI to maximize ROI and operational efficiency.

---

