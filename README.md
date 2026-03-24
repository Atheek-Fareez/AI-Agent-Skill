🚀 AI Agent Skill for Hospital Management System
🧠 Overview

This project demonstrates a custom AI Agent Skill designed for a Hospital Management System (HIMS).

Instead of using AI as a generic chatbot, this project focuses on controlling LLM behavior through structured instructions, workflows, and domain-specific rules.

💡 Key Idea

Most AI applications rely on open-ended prompts.

This project takes a different approach:

👉 It teaches the AI how to behave using a defined skill.

⚙️ What the Agent Skill Does

The AI is designed to:

✔ Follow real hospital workflows
✔ Understand patient registration, billing, and appointments
✔ Respond in structured, step-by-step format
✔ Avoid hallucinations using predefined rules
✔ Maintain domain-specific consistency
🧠 Skill Design Approach

The Agent Skill is implemented using a SKILL.md file that defines:

🔹 Project Context
Hospital Management System (HIMS)
🔹 Workflow Logic
Patient Registration
Appointment Booking
Billing Process
🔹 Behavior Rules
No medical diagnosis
Structured responses
Simple and clear explanations
Real-world workflow adherence
🏗️ Skill Structure
.agents/
 └── skills/
      └── hospital-assistant/
           └── SKILL.md
⚙️ Example Capability
Input
How does patient registration work?
Output
1. Check if patient exists  
2. Create a new patient ID if not found  
3. Store patient details  
4. Proceed to appointment booking  
🧪 Testing

The skill is tested using Gemini CLI, which reads the SKILL.md file and applies the defined rules and workflows during interaction.

🎯 Key Learning

AI is not just about prompts.
It’s about designing behavior, rules, and workflows.

This project highlights:

Agent Skill Design
Prompt Engineering
Workflow Modeling
Controlled AI Behavior
🚀 Future Improvements
Connect skill with real-time database
Enable tool-calling (AI performs actions)
Build multi-agent architecture
Integrate into full production systems
🧩 Tech Stack
Google Gemini API
Gemini CLI
Markdown-based Skill Definition (SKILL.md)
📌 Summary

This project demonstrates how to transform an LLM from a generic chatbot into a domain-specific intelligent agent using structured skill design.
