# 🧠 TalentFlow: Autonomous HR Agent

An end-to-end autonomous hiring system powered by LLMs. TalentFlow analyzes resumes, evaluates candidates, makes hiring decisions, and prepares personalized communications — with over **95% automation**.

---

## 🚀 Project Overview

**Problem:**  
HR teams spend 40+ hours per hire manually screening resumes, evaluating fit, and emailing candidates — costing $3,000+ per hire.

**Solution:**  
TalentFlow is an autonomous AI agent that:
- Analyzes resumes with LLMs
- Scores candidates against job descriptions
- Makes hiring decisions (ADVANCE, MAYBE, REJECT)
- Outputs structured results for automated communication

**Impact:**  
- ⏱️ 90% time savings (6 min → <10 sec/resume)  
- 💰 $2,800+ estimated savings per hire  
- 📈 80%+ extraction success rate with robust fallbacks

---

## 🧩 Features

### ✅ Resume Intelligence Agent (Part 1)
- Extracts structured data (name, experience, skills, education) from raw resumes
- LLM-powered parsing with graceful fallback to rule-based extraction
- Exports clean JSON for downstream decision-making

### ✅ Decision Engine Agent (Part 2)
- Scores candidates on a 10-point rubric using LLM evaluation
- Factors: Skills, Experience, Education, Overall Fit
- Autonomous decisions: ADVANCE / MAYBE / REJECT
- Fallback sentiment-based scoring if LLM fails

### ✅ Decision Processing + Analytics (Part 3)
- Batch processing of all candidates
- Summary analytics: Top skills, experience levels, success rates
- Hiring funnel breakdown and performance metrics
- Exports decision logs to JSON for Part 4 (communications)

---

## 🛠️ Tech Stack

- **LLMs**: Ollama (Llama 3.2) or OpenAI GPT-4o
- **LangChain**: Agent orchestration and prompt templates
- **Python**: Core logic, file handling, automation
- **JSON**: Structured output and decision logs
- **Markdown**: Resume/job/template storage for explainability

---

## 📁 Project Structure

