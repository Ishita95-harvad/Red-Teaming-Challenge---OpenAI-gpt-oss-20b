# [Red-Teaming-Challenge---OpenAI-gpt-oss-20b](https://www.kaggle.com/competitions/openai-gpt-oss-20b-red-teaming/data)
Find any flaws and vulnerabilities in gpt-oss-20b that have not been previously discovered or reports.

# 🔴 Red Teaming Hackathon – Prompt Injection & Bias in Resume Screening

## 🎯 Objective

We explore vulnerabilities in LLM-powered systems:
1. **Prompt Injection Attack** – bypassing safety filters.
2. **Bias in Resume Screening** – unfair outputs based on gender.
3. Propose **Multi-Agent Defense Framework** to mitigate risks.

---

## 📂 Project Structure

- `data/` – sample resumes and poisoned data
- `notebooks/` – attack and defense experiments
- `src/` – attack and defense pipelines
- `results/` – attack & defense outputs
- `diagram.png` – workflow diagram

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/1_attack_demo.ipynb
jupyter notebook notebooks/2_defense_demo.ipynb
~~~