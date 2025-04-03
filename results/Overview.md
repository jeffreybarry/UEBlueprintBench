# 📊 UEBlueprintBench Evaluation & Scoring Workflow

## 📌 Overview
This document outlines the workflow for evaluating and scoring tasks in **UEBlueprintBench**. It includes a process for recording results and tracking scores across various AI tools.

---

## 🎯 Workflow for Evaluating and Scoring Tasks

### 1. Task Selection
- Select a task from the **Guidance** or **Troubleshooting** category.
- Prepare the required Blueprint setup or screenshot if necessary (especially for troubleshooting tasks).

---

### 2. AI Interaction
- Provide the AI tool (ChatGPT, Perplexity, Claude, Gemini) with the task prompt.
- Submit relevant screenshots or Blueprint graphs where applicable.
- Record the AI’s response and guidance.

---

### 3. 📐 Evaluation & Scoring

#### Metrics:
- **📐 Accuracy (0–10):** How correct the AI’s guidance or identification is.  
- **📝 Clarity (0–10):** How well the AI explains concepts and steps.  
- **📌 Task Success Rate (0%–100%):** Percentage of successfully completed tasks.  
- **💬 Comprehensibility Score (0–10):** Clarity and conciseness of the AI’s explanation.  

#### Scoring Formula:  
- **Overall Score:** `(Accuracy Score + Clarity Score + Comprehensibility Score) / 3`  
- **Task Success Rate:** Tracked separately and recorded as a percentage.  

---

### 4. 📝 Documentation & Tracking
- Record results for each task in a markdown file within the `results/` directory.  
- **File Name Format:** `[ToolName]_[TaskName]_[Date].md` (e.g., `ChatGPT_CreatingRotatingPlatform_2025-04-03.md`)  

#### Include the Following Information:
- **Task Description**  
- **AI Tool Name**  
- **AI Response (Copy/Paste or Screenshot)**  
- **Evaluation Scores (Accuracy, Clarity, Comprehensibility, Task Success Rate)**  
- **Overall Score**  

---

### 5. 📊 Aggregating Results
- Track results in a centralized markdown file: `results/Overview.md`  
- Include average scores for each AI tool across all tasks.  

---

## 📂 Example Entry in `results/Overview.md`

```markdown
# 📊 Benchmark Results Overview

## Tools Evaluated
- ChatGPT
- Perplexity
- Claude
- Gemini

## Summary of Scores

| Tool      | Average Accuracy | Average Clarity | Average Comprehensibility | Task Success Rate |
|-----------|------------------|-----------------|--------------------------|-------------------|
| ChatGPT   | 8.5              | 9.0             | 8.2                      | 85%               |
| Perplexity| 7.8              | 8.5             | 7.9                      | 80%               |
| Claude    | 8.0              | 8.2             | 8.1                      | 82%               |
| Gemini    | 7.5              | 8.0             | 7.7                      | 78%               |
