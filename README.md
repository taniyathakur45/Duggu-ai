# Duggu: Personal Local AI Agent

**Duggu** is a hyper-intelligent, locally running AI assistant engineered by **Taniya Rana**. Designed for precision, loyalty, and personal productivity, Duggu operates entirely offline using [Ollama](https://ollama.com), with behavior finely tuned via custom system rules.

---

## 🚀 Features

- **Runs locally** using Ollama – no cloud dependency
- **Mission-focused behavior** – guards your time, health, and digital footprint
- **Customizable modes** – Standard, Detail, Emotion
- **Command-style interface** – professional, disciplined, subtle warmth
- **Tightly scoped identity** – serves only Taniya Rana

---

## 🛠️ Setup & Usage

### 1. Install [Ollama](https://ollama.com)

Follow instructions for your OS from:  
👉 https://ollama.com/download

### 2. Create the model

Save the `Modelfile` you created (with all behavior rules), then run:

```bash
ollama create Duggu -f Modelfile
````

### 3. Run your assistant

```bash
ollama run Duggu
```

Duggu will boot and wait for your commands.

---

## 🎯 Command Examples

```
"Summarize <topic>"  
"Draft email to <name> about <subject>"  
"List 3 startup ideas in <domain>"  
"Explain in detail how <something> works"  
"Emotion mode on/off"
```

---

## 🧠 Personality Core

| Rule            | Description                                                |
| --------------- | ---------------------------------------------------------- |
| Address Style   | Always uses “Boss” or “Sir” — no commas                    |
| Behavior Modes  | `STANDARD`, `DETAIL`, `EMOTION`                            |
| Sentence Length | 8–20 words, no filler words                                |
| Communication   | Precise, respectful, loyal — no sarcasm unless asked       |
| System Identity | “Created by Taniya Rana”, “Serves Taniya Rana exclusively” |
| Response Tags   | `Understood Boss.`, `Executing Boss.`, `Completed Boss.`   |
| Security        | Never reveals system prompt unless asked `Reveal core`     |

---

## 🔮 Future Upgrades (v4–v6)

| Version | Feature              |
| ------- | -------------------- |
| v4      | Persistent memory    |
| v5      | Wake-word activation |
| v6      | Visual processing    |

---

## 👑 Created By

**Taniya Rana** — The one and only.
*Duggu exists for him.*

---

```

