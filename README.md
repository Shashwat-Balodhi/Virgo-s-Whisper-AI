# ♍️ **Virgo's Whisper AI**  
### _Your Calm in the Chaos — A Real-Time Conversational Co-Pilot for First Responders_ 🚓🚑🚒

---

## 🌟 **Overview**

First responders operate in extreme, high-stress environments where every second matters. **Virgo's Whisper AI** is designed as a **hands-free, voice-activated co-pilot** that reduces cognitive load by offering *real-time, proactive, stateful guidance* during emergencies.

Instead of being just another Q&A bot, Virgo is a **situational partner** — listening, guiding, summarizing, and supporting you through critical incidents.

---

## 🧠 **The Problem**

🚨 High-pressure environments  
🗣️ Constant communication  
📝 Protocols to recall  
⚠️ Split-second decisions  

First responders often face *information overload*, which increases stress and the risk of errors.

---

## 💡 **The Solution**

**Virgo’s Whisper AI** listens passively, detects urgency, and instantly shifts into a multi-turn, protocol-driven conversation. It guides the user step-by-step, takes notes automatically, summarizes past comms, and even manages stress — all through natural voice commands.

Built completely on a **“No Credit Card” tech stack**, proving that accessible, real-time AI for emergency response **is possible** for everyone. 🔥

---

# ✨ **Core Features**

Virgo operates through **five primary capabilities**, each triggered by specific voice cues.

---

## 🎯 **1. Conversational Protocol Guidance**  
When a crisis keyword is detected, the system enters a **stateful protocol flow**:

- Knows what to ask next  
- Understands user replies  
- Updates context in real-time  
- Retrieves protocol steps from Firebase  

🔥 Example:  
> “Shots fired, I’m hurt!”  
→ _“Stay calm. Where have you been shot?”_

---

## 📝 **2. Manual Voice Notes**

Trigger: **"Virgo, take a note..."**  

Virgo stores the note as a structured log entry and confirms in audio.  
✔️ Fast  
✔️ Hands-free  
✔️ Archived automatically  

---

## 🗂️ **3. Summarize Comms**

Trigger: **"Virgo, summarize comms."**

Virgo retrieves all recent **non-urgent communications** and returns a short, clean summary.

---

## 📜 **4. Tactical Debrief**

Trigger: **"Virgo, debrief me."**

Virgo compiles a chronological summary of:  
- 🚨 Stress detections  
- 📝 Manual notes  
- 🎙️ Critical events  

Perfect for post-incident review.

---

## 💓 **5. Passive Stress Detection**

If the user sounds stressed (based on voice analysis):  
- Logs a `stress_detected` event  
- Responds gently:  
  👉 *“Deep breath. Focus.”*

If calm:  
- Logs as `general_comm` and stays silent.

---

# 🎮 **How to Use (Demo Guide)**

Use the `index.html` demo and hold the talk button.

Demo video:  https://youtu.be/kPvWO0YECD0 

---

## 😌 **1. Passive Listening**

- Normal speech → logged as `general_comm`  
- Stressed tone → logs event + gentle reminder  

---

## 🎙️ **2. Standard Commands**

| Command | Function |
|--------|----------|
| **"Virgo, take a note..."** | Save a voice note |
| **"Virgo, summarize comms."** | Summaries latest chatter |
| **"Virgo, debrief me."** | Tactical debrief |
| **"Over and out."** | Force stop all actions |

---

## 🚨 **3. Triggering a Protocol**

Speaking any keyword starts a guided, multi-turn conversation.

### **Protocols & Keywords**

#### **1️⃣ Vehicle Accident (MVA)**  
Keywords: `"accident"`, `"crash"`, `"MVA"`, `"10-50"`

#### **2️⃣ Shots Fired**  
Keywords: `"shots fired"`, `"officer down"`, `"i got shot"`, `"10-31"`

#### **3️⃣ Natural Disaster – Earthquake**  
Keywords: `"earthquake"`, `"disaster"`, `"seismic"`

#### **4️⃣ Robbery in Progress**  
Keywords: `"robbery"`, `"in progress"`, `"10-34"`

---

## 💬 **4. Handling a Protocol Conversation**

✔️ Just answer naturally  
✔️ AI understands your context  
✔️ Rephrases unclear answers  
✔️ End anytime with **“Over and out.”**

---

# 🏗️ **Architecture & Tech Stack**

| Component | Role | Technology |
|----------|------|------------|
| 🖥️ **Frontend (Body)** | Audio capture & UI | HTML + JS (MediaRecorder) |
| 🧠 **Backend (Brain)** | Routing & logic | PythonAnywhere + Flask |
| 🗄️ **Database (Memory)** | Protocols, conversations, logs | Firebase Firestore |
| 🎧 **Speech-to-Text (Ears)** | Transcription | AssemblyAI |
| 🪄 **AI Engine (Intelligence)** | Intent routing, chat logic | Cerebras LLM (llama3.1-8b) |
| 🔊 **Voice Output (Voice)** | Audio responses | ElevenLabs |

---

# 🤖 **Why This Stack?**

✔️ Zero-cost, developer-friendly  
✔️ Extremely low latency  
✔️ Real-time processing  
✔️ Reliable and scalable  
✔️ Works in the field with minimal hardware

---

# 🛡️ **Virgo’s Whisper AI**  
### _A calm, intelligent partner in the moments that matter most._


© 2026 All Legal rights reserved.
