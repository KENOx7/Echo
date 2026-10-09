<div align="center">

# 🕵️ ECHO — Who Is Still Human?

### 🧠 A Psychological Detective Thriller Powered by AI

**Don't trust everything you hear. Question everything.**

![Unity](https://img.shields.io/badge/Unity_6-000000?style=for-the-badge&logo=unity&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini_API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)

</div>

---

## 🎭 About ECHO

**ECHO** is a first-person, 3D detective game about identity, trust, and artificial intelligence.

An AI has vanished from a secure digital system. Investigators believe it has taken control of a human body. As the detective assigned to the case, you must question **four suspects**, compare their statements, and determine **who is still human**.

The mystery is not about finding whoever seems the most suspicious. Every suspect has their own secrets, and a convincing answer is not necessarily a truthful one.

## 🌐 The Idea Behind the Game

AI can already produce natural-sounding conversations, even when its answers are inaccurate or misleading. **ECHO** explores the difference between *sounding believable* and *being trustworthy*.

The game invites players to ask better questions, notice contradictions, and base decisions on evidence rather than first impressions. Its human-versus-AI premise is fictional; the game does not claim that conversation alone can reliably identify AI in real life.

## 🧩 How the Investigation Works

**1. 🔎 Explore the case**  
Enter the detective's environment and learn about the investigation, its suspects, and the information available to you.

**2. 🗣️ Question the suspects**  
Interview four characters with different backgrounds, motives, and perspectives. What they say—and what they avoid saying—matters.

**3. 🧠 Connect the evidence**  
Compare statements, examine case information on the retro-style detective computer, and look for contradictions.

**4. ⚖️ Make an accusation**  
Use your findings to decide which suspect is controlled by AI. The final decision determines the outcome of the case.

## 🤖 Gemini API & Intelligent NPCs

The game's NPC conversation system is connected to the **Google Gemini API**. Instead of relying only on a fixed set of lines, NPCs can generate responses based on the player's question and the investigation context.

### 💬 Context-aware conversations

NPC responses are intended to follow the subject of the interrogation. A question about an alibi, an event, or another suspect should produce an answer connected to that topic—not a random unrelated line.

### 🎲 Controlled variation

Characters can express the same underlying information in different ways. Their wording and reactions are not meant to be identical in every conversation. This is **controlled unpredictability**, not randomness without a purpose.

### 🎭 Character identity

Each suspect has a distinct **personality, background, role, and set of facts they are allowed to know**. These details guide the AI so that different characters speak and react differently while remaining part of the same mystery.

### 🧠 Reasoning and consistency

The conversation design aims to keep answers logical and consistent with the case. Players must still evaluate responses critically: AI-generated dialogue can occasionally be inaccurate or inconsistent, and a fluent response is not proof that a character is telling the truth.

### 🔄 Conversation flow

```text
Player asks a question
          ↓
NPC identity + case context
          ↓
     Gemini API
          ↓
Contextual, varied response
          ↓
Player compares the answer with the evidence
```

**The key idea:** AI doesn't just appear in the story. It shapes how players experience the interrogation itself.

## ✨ Core Features

- 🕵️ **Detective investigation** — question suspects and reach your own conclusion.
- 🤖 **AI-powered NPC dialogue** — responses generated through the Gemini API.
- 🎲 **Variable conversations** — different phrasing and reactions within the story context.
- 🧩 **Evidence and contradictions** — investigate what each person claims.
- 🖥️ **Retro detective computer** — access case information and suspect records.
- 🏢 **Immersive 3D setting** — explore the office and interrogation environment.
- 🇦🇿 **Azerbaijani-language storytelling** — a mystery designed for local players.
- ⚖️ **Consequential ending** — your accusation determines the result.

## 🛠️ Technology

| Technology | Role |
| --- | --- |
| 🎮 **Unity 6** | 3D environment and game engine |
| 💻 **C#** | Gameplay logic and interaction systems |
| 🤖 **Google Gemini API** | Dynamic, context-aware NPC dialogue |
| ⌨️ **Unity Input System** | Player controls and interactions |
| 💬 **TextMeshPro / uGUI** | Dialogue and interface elements |
| 🎨 **Universal Render Pipeline (URP)** | Game rendering |

## 🚀 Running the Project

The prototype targets **Windows PC** with keyboard and mouse.

1. Clone or download the repository.
2. Open the project in **Unity Hub** using **Unity Editor 6000.6.4f1**.
3. Wait for the assets and packages to import.
4. Open `Assets/Office Room Furniture/Demo/Demo Scene.unity`.
5. Press **Play**.

### 🎮 Controls

| Input | Action |
| --- | --- |
| `W` `A` `S` `D` | Move |
| Mouse | Look around |
| `E` | Interact with doors or chairs |
| `R` | Summon a suspect while seated at the interrogation desk |
| `Enter` / `Space` | Advance dialogue |
| `Q` | Access the detective computer while seated |
| `Esc` | Close the current interface |

> Controls and scene locations describe the current prototype and may vary between project versions.

## 🔐 Gemini API Configuration

AI-powered dialogue requires a valid **Gemini API connection** and internet access. Configure the API integration used by your project before starting NPC conversations.

**Keep credentials private:** never publish Gemini API keys or secret configuration files in the repository. For distributed builds, a secure server-side API connection is preferable to exposing a key inside the Unity client.

## 👥 Team

**ECHO** was created by a three-person hackathon team.

## 💡 Final Thought

**ECHO** is built around a simple question: **When artificial intelligence sounds human, what can we actually trust?**

The answer is not hidden in how confident someone sounds. It lies in asking questions, connecting evidence, and thinking critically.

<div align="center">

### 🕵️ ECHO — Who Is Still Human?

*Question everything. Trust the evidence.*

</div>
