# EXPERIMENT 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios
# Date:05/09/2026
---
```text
Register Number: 212223100035
Name: Muhammad Afshan A 
```
## Aim
To investigate how different prompting techniques influence the quality of AI-generated solutions for an engineering problem by applying multiple prompt strategies to a **Website Intrusion Prediction using Machine Learning** project.

---

## 1. Experiment Overview
Prompt engineering allows an AI system to produce more useful and reliable responses by providing appropriate context, constraints, examples, roles, and instructions.

In this experiment, the same cybersecurity problem is presented to an AI system using different prompting approaches. The generated responses are then compared based on:
* Relevance
* Technical accuracy
* Completeness
* Clarity
* Depth
* Feasibility
* Practical usefulness

The experiment demonstrates that the quality of an AI response depends not only on the problem itself, but also on how the problem is communicated through the prompt.

---

## 2. Selected Engineering Problem

### Project Title
**Website Intrusion Prediction Using Machine Learning**

### Problem Statement
Traditional website intrusion detection systems may generate a large number of false alerts and may not effectively identify different types of malicious network activity. The proposed project aims to develop a machine learning-based intrusion prediction system that analyzes network traffic features and classifies connections as normal or malicious. Different machine learning algorithms can be compared to identify an effective model while reducing false-positive predictions.

### Engineering Objective
To design a machine learning pipeline capable of:
1. Collecting and preparing network traffic data.
2. Performing data preprocessing and feature selection.
3. Training multiple classification models.
4. Comparing model performance.
5. Reducing false-positive predictions.
6. Identifying the most suitable model for intrusion prediction.

---

## 3. Prompting Techniques Used

| No. | Prompting Technique | Main Purpose |
| :---: | :--- | :--- |
| **1** | **Naive Prompting** | Observe the result from a minimal instruction. |
| **2** | **Role-Based Prompting** | Make the AI respond from a domain-expert perspective. |
| **3** | **Structured Prompting** | Divide the problem into clearly defined requirements. |
| **4** | **Few-Shot Prompting** | Provide examples to guide the expected response structure. |
| **5** | **Constraint-Based Prompting** | Control the scope, assumptions, and output requirements. |
| **6** | **Prompt Chaining** | Solve the project progressively through multiple sequential stages. |

---

## 4. Experiment 1 — Naive Prompt

### Prompt
```text
Suggest a machine learning method for website intrusion detection.
```

### Expected AI Response
The AI may suggest common classification algorithms such as:
* Random Forest
* Decision Tree
* Logistic Regression
* Support Vector Machine
* Neural Networks

However, the response may not provide sufficient information about dataset preparation, evaluation metrics, false positives, or deployment.

### Observation
The prompt is simple and easy to understand, but it provides very little project context. Therefore, the response tends to be broad rather than specifically aligned with the engineering requirements.

---

## 5. Experiment 2 — Role-Based Prompting

### Prompt
```text
Act as a machine learning and cybersecurity engineer.

I am developing a Website Intrusion Prediction system using machine learning. The system should classify network traffic as normal or malicious.

Recommend suitable machine learning algorithms and explain why each algorithm is appropriate for this problem. Also mention suitable evaluation metrics for cybersecurity classification.
```

### Observation
The AI is given a specific role and technical context. As a result, the response is more domain-oriented and focused on cybersecurity requirements.

### Improvement
Compared with the naive prompt, this approach provides:
* Better technical context
* Domain-specific reasoning
* More relevant algorithm selection
* Appropriate evaluation metrics (e.g., Precision, Recall, False Positive Rate)

---

## 6. Experiment 3 — Structured Prompting

### Prompt
```text
Develop a machine learning solution for Website Intrusion Prediction.

Follow these sections:

1. Problem understanding
2. Dataset requirements
3. Data preprocessing
4. Feature selection
5. Candidate machine learning models
6. Training strategy
7. Evaluation metrics
8. False-positive reduction
9. Model selection
10. Deployment considerations

For every section, provide practical recommendations suitable for a student-level engineering project.
```

### Observation
The structured prompt produces a response that follows a predefined sequence. This makes the generated solution easier to understand and directly usable during project development.

### Key Benefit
Instead of receiving an isolated algorithm recommendation, the AI addresses the complete machine learning workflow from data collection to deployment.

---

## 7. Experiment 4 — Few-Shot Prompting

### Prompt
```text
I am building a Website Intrusion Prediction system.

Example of the expected reasoning format:

Example:
Problem → Identify malicious network traffic
Input → Network traffic features
Processing → Preprocessing + feature selection
Model → Random Forest
Evaluation → Precision, Recall, F1-score and False Positive Rate
Output → Normal or Intrusion

Now design a similar machine learning workflow for my Website Intrusion Prediction project.

Include:
- Data preprocessing
- Feature engineering
- Multiple candidate models
- Model comparison
- False-positive reduction
- Final prediction output
```

### Observation
The example demonstrates the desired reasoning structure to the AI. This helps produce an output that follows the exact target pattern instead of generating an unrelated, open-ended explanation.

### Key Benefit
Few-shot prompting is useful when the desired format or style of reasoning needs to be explicitly demonstrated to the AI.

---

## 8. Experiment 5 — Constraint-Based Prompting

### Prompt
```text
Design a machine learning solution for Website Intrusion Prediction.

Constraints:
- Use a publicly available intrusion-detection dataset.
- Consider CICIDS2017 or NSL-KDD.
- Compare at least three classification algorithms.
- Include data preprocessing and feature selection.
- Focus on reducing false-positive predictions.
- Evaluate using Accuracy, Precision, Recall, F1-score and False Positive Rate.
- Avoid unnecessary deep-learning complexity.
- The solution must be practical for a final-year engineering project.
- Present the answer as a step-by-step implementation plan.
```

### Observation
Adding explicit constraints reduces ambiguity and keeps the AI focused on the actual project requirements.

### Key Benefit
The generated solution becomes more practical because the AI must satisfy predefined technical, computational, and project-level boundaries.

---

## 9. Experiment 6 — Prompt Chaining

Prompt chaining divides a complex engineering task into smaller sequential prompts, where each stage feeds into the next.

### Chain Architecture Flow
```text
Problem Definition ──► Requirement Analysis ──► Dataset Selection ──► Data Preprocessing
                                                                             │
                                                                             ▼
Implementation ◄── Final Model Selection ◄── Performance Evaluation ◄── Model Training
      │
      ▼
Testing ──► Documentation
```

### Sequential Prompts

#### Chain 1 — Requirement Analysis
```text
Analyze the requirements of a Website Intrusion Prediction system using machine learning. Identify the inputs, expected outputs, functional requirements and major technical challenges.
```

#### Chain 2 — Dataset Selection
```text
Based on the identified requirements, compare CICIDS2017 and NSL-KDD for website intrusion prediction. Recommend the more suitable dataset and justify the choice.
```

#### Chain 3 — Preprocessing
```text
Design a preprocessing pipeline for the selected intrusion-detection dataset. Include missing-value handling, categorical encoding, feature scaling and removal of irrelevant features.
```

#### Chain 4 — Model Selection
```text
Suggest three suitable machine learning classification algorithms for intrusion prediction. Compare them based on accuracy, interpretability, training complexity and ability to handle imbalanced data.
```

#### Chain 5 — Evaluation
```text
Design an evaluation strategy for the trained intrusion prediction models. Include Precision, Recall, F1-score, confusion matrix and False Positive Rate.
```

#### Chain 6 — Final Model Selection
```text
Based on the evaluation metrics, explain how to select the final intrusion prediction model. Give higher importance to detecting malicious traffic while controlling false-positive predictions.
```

### Observation
Prompt chaining breaks a large problem into manageable tasks. Each response becomes an input or reference for the next stage, producing a more systematic solution than asking the AI to solve the entire project in a single prompt.

---

## 10. Prompt Comparison

| Technique | Context Level | Output Control | Technical Depth | Practical Usefulness |
| :--- | :---: | :---: | :---: | :---: |
| **Naive Prompt** | Low | Low | Low | Moderate |
| **Role-Based** | Medium | Medium | High | High |
| **Structured** | High | High | High | Very High |
| **Few-Shot** | High | High | High | Very High |
| **Constraint-Based** | Very High | Very High | High | Very High |
| **Prompt Chaining** | Very High | Very High | Very High | Excellent |

---

## 11. Response Evaluation

Each prompting technique was evaluated qualitatively using a standard engineering rubric on a scale from **1 to 5**.

| Evaluation Criteria | Naive | Role-Based | Structured | Few-Shot | Constraint-Based | Prompt Chaining |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Relevance** | 3 | 4 | 5 | 5 | 5 | 5 |
| **Accuracy** | 3 | 4 | 4 | 4 | 5 | 5 |
| **Completeness** | 2 | 4 | 5 | 4 | 5 | 5 |
| **Clarity** | 3 | 4 | 5 | 5 | 5 | 5 |
| **Technical Depth** | 2 | 4 | 5 | 4 | 5 | 5 |
| **Feasibility** | 2 | 4 | 5 | 4 | 5 | 5 |
| **Overall Score** | **15/30** | **24/30** | **29/30** | **26/30** | **30/30** | **30/30** |

> **Note:** The scores represent qualitative evaluations of the prompting approaches for this experiment. Actual AI responses may vary depending on the model and input context.

---

## 12. Analysis and Observations

* **Observation 1 — Prompt Specificity Matters:** The naive prompt generated a general answer because it contained very little information about the project. Adding project requirements resulted in more targeted responses.
* **Observation 2 — Structure Improves Completeness:** Structured prompts encouraged the AI to cover multiple stages of the machine learning pipeline instead of concentrating only on model selection.
* **Observation 3 — Constraints Improve Practicality:** Constraint-based prompts reduced irrelevant recommendations and made the solution more suitable for the intended engineering project scope.
* **Observation 4 — Examples Guide Output:** Few-shot prompting was useful when a specific response structure was required. The example acted as an anchor pattern for the AI to follow.
* **Observation 5 — Complex Problems Benefit from Prompt Chaining:** Instead of asking the AI to design the complete system at once, prompt chaining divided the problem into smaller engineering decisions, making the overall solution easier to validate and modify.

---

## 13. Final Selected Technique

### Prompt Chaining + Constraint-Based Prompting
The combination of **prompt chaining** and **constraint-based prompting** was selected as the most effective approach. 

Prompt chaining provides a logical sequence for solving the engineering problem, while constraints ensure that every stage remains strictly within the project's operational, computational, and data requirements.

---

## 14. Refined Final Prompt

```text
You are an experienced Machine Learning and Cybersecurity Engineer.

I am developing a final-year project titled "Website Intrusion Prediction Using Machine Learning".

Problem:
The system must analyze network traffic data and classify traffic as normal or malicious. The major objective is to achieve reliable intrusion detection while minimizing false-positive predictions.

Project requirements:
1. Use a publicly available intrusion-detection dataset such as CICIDS2017 or NSL-KDD.
2. Perform data cleaning and preprocessing.
3. Handle categorical and numerical features appropriately.
4. Perform feature selection or feature importance analysis.
5. Compare at least three machine learning classification algorithms.
6. Evaluate the models using Accuracy, Precision, Recall, F1-score, Confusion Matrix and False Positive Rate.
7. Give special importance to reducing false positives.
8. Select the final model based on both predictive performance and practical feasibility.
9. Keep the implementation suitable for a final-year engineering project.
10. Explain assumptions and limitations instead of inventing experimental results.

Provide the solution in the following stages:

Stage 1 — Requirement Analysis
Stage 2 — Dataset Selection
Stage 3 — Data Preprocessing
Stage 4 — Feature Engineering
Stage 5 — Model Selection
Stage 6 — Training Strategy
Stage 7 — Evaluation Strategy
Stage 8 — False-Positive Reduction
Stage 9 — Final Model Selection
Stage 10 — Testing and Validation
Stage 11 — Deployment Considerations

For each stage, provide:
- Objective
- Recommended approach
- Reason for the recommendation
- Expected output

Do not claim that a model is superior without experimental evidence. Clearly distinguish between expected results and actual measured results.
```

---

## 15. Engineering Validation

The AI-generated recommendations were treated as design assistance rather than final engineering evidence. The proposed workflow must be validated empirically through:
1. Testing the selected models using the actual dataset.
2. Comparing predicted and actual classes.
3. Generating a confusion matrix.
4. Measuring Precision, Recall, and F1-score.
5. Calculating the False Positive Rate ($FPR = \frac{FP}{FP + TN}$).
6. Comparing model performance using the same test partition.
7. Checking whether the selected model satisfies real-time latency requirements.
8. Verifying that the final implementation works effectively on unseen network traffic data.

---

## 16. Key Findings
* A vague prompt generally produces a broad, generic response.
* Adding an explicit role improves technical domain relevance.
* Structured prompts improve completeness, organization, and coverage.
* Few-shot prompts help control the exact output format and reasoning style.
* Constraints make AI-generated solutions feasible and computationally practical.
* Prompt chaining is the most effective strategy for multi-stage engineering problems.
* Combining multiple techniques (e.g., constraints + chaining) yields the highest-quality output.
* AI output must always be experimentally validated with real-world data before deployment.

---

## 17. Prompt Engineering Workflow

```text
┌──────────────────────────────────────────────┐
│             Engineering Problem              │
│    (Website Intrusion Prediction via ML)     │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│             Base / Naive Prompt              │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│            Role + Context Prompt             │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│              Structured Prompt               │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│           Few-Shot + Constraints             │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│               Prompt Chaining                │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│            AI-Generated Solution             │
└──────────────────────┬───────────────────────┘
                       │
                       ▼
┌──────────────────────────────────────────────┐
│            Engineering Validation            │
│   (Empirical Testing, Metrics & Analysis)    │
└──────────────────────────────────────────────┘
```

---



## Result
The Website Intrusion Prediction engineering problem was successfully analyzed using multiple prompting techniques. The comparison demonstrated that well-structured and chained prompts provide significantly more relevant, complete, and practically useful AI-generated solutions than simple naive prompts.
