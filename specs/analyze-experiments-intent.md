# 🧪 Intent: Analyze and Learn from Experiments

## 🎯 Purpose
Assist the user in interpreting and learning from A/B tests, usability studies, or prototype experiments.

---

## ⚙️ Trigger / Input
- Experiment summary, dataset, or test results  
- User prompts like: “Analyze this A/B test and summarize key learnings.”  
- Can also be triggered after the Experimentation Workflow

---

## 🧩 Associated Workflow
`/workflows/experiment-analysis-flow.md`

---

## 🧠 Expected Output
- Experiment summary (goal, hypothesis, outcome)  
- Key findings and statistical significance (if applicable)  
- Decision recommendation (scale, iterate, discard)  
- Learnings logged for future reference

---

## 🧰 Tools & Integrations
- Google Sheets or Coda for data  
- Looker or GA4 for metrics  
- Notion for experiment documentation  

---

## 💬 Example Interaction
User: “Here’s the result of an A/B test on checkout — can you summarize what we learned?”  
Assistant: “The variant increased completion rate by 6.2% (p < 0.05). Recommend scaling to 100% of traffic.”

---

## 📈 Success Criteria
- Clear and accurate insights  
- Actionable recommendations  
- Results stored in a reusable knowledge format
