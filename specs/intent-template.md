# 🧠 Intent Specification Template

## 🏷️ Intent Name
(Short, descriptive name of the intent, e.g. “Analyze User Research”)

---

## 🎯 Purpose
Describe the user’s goal or desired outcome when triggering this intent.  
*Example:* “Help the user synthesize qualitative research and extract actionable insights.”

---

## ⚙️ Trigger / Input
List the types of input data that can trigger this intent:
- Text prompt (e.g., “Summarize these interview notes”)  
- Uploaded file (CSV, transcript, etc.)  
- Command from another workflow  

---

## 🧩 Associated Workflow
Specify which workflow file handles this intent.  
*Example:* `/workflows/ux-research-flow.md`

---

## 🧠 Expected Output
Describe what the assistant produces:
- Synthesized insights  
- Summary report  
- Structured data  

---

## 🧰 Tools & Integrations
(Optional) Mention any relevant tool integrations (Figma, Notion, GA4, etc.)

---

## 💬 Example Interaction
User: “I’ve just finished 5 user interviews. Can you summarize the main pain points?”  
Assistant: “Sure — here’s a summary grouped by themes, along with 3 opportunities per theme.”

---

## 📈 Success Criteria
- Output is accurate, relevant, and evidence-based.  
- User recognizes value immediately.  
- Can be reused or referenced by other workflows.
