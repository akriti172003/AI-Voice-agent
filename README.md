# AI-Voice-agent
AI-Voice Receptionist ALLY
# 🦷 Ally – AI Voice Receptionist for SmileCare Dental Clinic

## 🚀 Overview

**Ally** is an AI-powered voice receptionist built for **SmileCare Dental Clinic** using **Vapi, OpenAI, Deepgram, and ElevenLabs**. It simulates a professional front desk receptionist capable of handling patient calls naturally through voice conversations.

The goal of this project is to automate common clinic interactions while providing a human-like experience, reducing receptionist workload and improving customer support.

---

# ✨ Features

* 📞 Natural voice conversations
* 📅 Appointment booking assistance
* 🔄 Appointment rescheduling and cancellation
* 👩‍⚕️ Doctor schedule information
* 🏥 Clinic timings and location assistance
* 🦷 Answers to common dental procedure FAQs
* 🚨 Emergency call handling and escalation
* 🔒 Patient privacy protection
* 📧 Email information sharing (via integrated tool, when configured)
* 🤝 Human-like conversational flow with empathy and professionalism

---

# 🛠️ Tech Stack

* **Vapi** – Voice Agent Platform
* **OpenAI GPT** – Conversational reasoning
* **Deepgram** – Speech-to-Text (STT)
* **ElevenLabs** – Text-to-Speech (TTS)
* **Prompt Engineering** – System behavior and workflows
* **MCP (Model Context Protocol)** – Tool integration for external actions

---

# 🏗️ Architecture

Caller Speech

↓

Deepgram (Speech-to-Text)

↓

OpenAI GPT (Reasoning & Decision Making)

↓

System Prompt + Conversation Context

↓

Tool Execution (Appointment / Email / etc.)

↓

ElevenLabs (Text-to-Speech)

↓

Voice Response to Caller

---

# 📋 Capabilities

The assistant can:

* Greet callers professionally
* Collect appointment details
* Guide patients to the appropriate doctor
* Answer questions about clinic timings and location
* Explain common dental procedures in simple language
* Handle emergency situations by directing patients appropriately
* Maintain strict privacy by never revealing another patient's information
* Escalate queries that require human staff intervention

---

# 🔐 Safety & Privacy

The assistant is designed with strict guardrails:

* Never diagnoses diseases
* Never prescribes medication
* Never guarantees treatment outcomes
* Never fabricates appointment availability
* Never shares another patient's information
* Escalates unsupported requests to clinic staff

---

# 💡 Sample Conversation

**Patient:** Hi, I'd like to book an appointment for a toothache.

**Ally:** Certainly! May I have your name and phone number?

**Patient:** Rahul Sharma, 9876543210.

**Ally:** Thank you. Do you have a preferred doctor or date for your appointment?

---

# 🎯 Learning Outcomes

Through this project, I learned:

* Agentic AI concepts
* Prompt Engineering
* Voice AI development
* Conversational workflow design
* Real-time speech processing
* AI safety and privacy principles
* Tool integration using MCP

---



