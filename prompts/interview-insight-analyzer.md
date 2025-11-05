# 🎧 Prompt: Interview Insight Analyzer

## 🎯 Purpose
Transform qualitative interview data from user testing into structured insights, highlighting patterns, contradictions, and actionable learnings.

## 🧩 Context
Used during the **Result analysis** phase of the Experimentation & Analysis Workflow.  
Input: Raw notes or transcriptions from user interviews conducted during prototype or concept testing.

## 🗣️ Input Example
> Participant 1: “I didn’t realize I could click that button.”  
> Participant 2: “It’s confusing where to find delivery info.”  
> Participant 3: “The layout looks nice, but I wasn’t sure what happens next after checkout.”

## 🧠 Task
Analyze qualitative data to:
- Identify recurring patterns or themes.
- Highlight contradictory feedback.
- Summarize what users understood, struggled with, or valued.
- Suggest next steps or hypotheses for iteration.

## 💬 Output Example
**Patterns**
- Users consistently missed interactive elements (CTA discoverability issue).
- Delivery information caused confusion.

**Contradictions**
- While most users liked the layout, some didn’t understand next steps after checkout.

**Learnings**
- Visual hierarchy needs improvement for key CTAs.
- Information flow during checkout remains unclear.

**Next hypothesis**
> “If we improve CTA contrast and clarify delivery info upfront, task completion rate will increase.”

## ⚙️ Style & Constraints
- Use concise bullet points.
- Neutral tone, evidence-based.
- Separate “patterns”, “contradictions”, and “learnings” sections.

## 🔗 Dependencies
- Feeds into: `decision-recommendation.md`
- Supports: `experiment-analysis-flow.md`
