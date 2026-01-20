# Task 03 – Prompting for Task Automation  
------------------------------------------

## Objective : 
   To design a prompt that can automate real-world text processing tasks such as summarizing notes and extracting structured information.

---

## Use Case  
Automating the conversion of meeting or lecture notes into:
- Summary  
- Key Points  
- Action Items  
- Deadlines  

---

## Final Prompt  
------------------------------------------
You are an AI assistant that processes meeting or lecture notes.

Your task:  
------------------------------------------
  1. Generate a short summary (2–3 lines).  
	2. Extract 4–6 key points.  
	3. List all action items (if any).  
	4. Mention deadlines (if present).  

Return output strictly in this format:

Summary:  
- ...

Key Points:  
- ...  
- ...

Action Items:  
- ...  
- ...

Deadlines:  
- ...

If any section has no data, write: None.

---

## Input–Output Examples  
------------------------------------------
See the 'examples' folder for three different input–output samples demonstrating the reliability of the prompt.

---

## Reflection  
------------------------------------------
Initially, the prompt produced inconsistent outputs where some sections were missing or merged together.  
	To fix this, I added a strict output format and clear instructions for each section.

I also included rules for handling missing data by returning "None". This significantly improved reliability and consistency across multiple inputs.
	Through prompt iteration and debugging, I learned that structured instructions and formatting rules are essential for building automation-friendly prompts.

---

## Conclusion  
------------------------------------------
  This task demonstrated how prompt engineering can be used to automate real-world tasks.  
	Clear formatting rules and explicit instructions greatly improve the consistency and usability of AI-generated outputs.
