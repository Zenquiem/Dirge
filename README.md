<div align="center">

<pre>
  ,gggggggggggg,
 dP"""88""""""Y8b,
 Yb,  88       `8b,
  `"  88        `8b gg
      88         Y8 ""
      88         d8 gg     ,gggggg,    ,gggg,gg   ,ggg,
      88        ,8P 88     dP""""8I   dP"  "Y8I  i8" "8i
      88       ,8P' 88    ,8'    8I  i8'    ,8I  I8, ,8I
      88______,dP'_,88,_,dP      Y8,,d8,    ,d8I  `YbadP'
     888888888P"  8P""Y88P      `Y8P"Y888888P"888888P"Y888
                                  ,d8I'
                                ,dP'8I
                               ,8"  8I
                               I8   8I
                               `8, ,8I
                                `Y8P"
</pre>

### 💀 Singing the final song for the vulnerable.

![Status](https://img.shields.io/badge/Status-Early_Access-critical)
![Focus](https://img.shields.io/badge/Focus-Binary_Exploitation-red)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## 📖 Introduction

**Dirge** is an experimental AI-powered agent designed for **Binary Exploitation (Pwn)**. 

Unlike general-purpose coding assistants, Dirge is being trained to understand the dark arts of memory corruption. It aims to bridge the gap between human intuition and machine automation in CTF competitions.

> *"Orchestrating the Inevitable."*

## 🛠️ Core Philosophy

Dirge follows a "Human-in-the-Loop" architecture:
1.  **Analyze**: Automated checksec and protection analysis.
2.  **Reason**: LLM-driven strategy formulation (Stack Overflow, ROP, Format String).
3.  **Execute**: Generating `pwntools` scripts and interacting with GDB.

## 🚀 Roadmap (The 8:2 Plan)

Currently in **Stealth Development**. The goal is to build a tool that grows alongside a freshman Pwn learner.

- [x] **Phase 0: Awakening**
    - [x] Basic Project Structure
    - [x] Checksec Integration
- [ ] **Phase 1: The Stack**
    - [ ] Auto-detect Buffer Overflow offset (Cyclic pattern)
    - [ ] Ret2text automation
    - [ ] Ret2libc chain generation (w/ LibcSearcher)
- [ ] **Phase 2: The Logic**
    - [ ] GDB State Analysis (Parsing registers & stack via Python)
    - [ ] Canary bypass strategies
- [ ] **Phase 3: The Heaps (Future)**
    - [ ] Tcache/Fastbin attack templates

## 📦 Requirements

* Python 3.10+
* [Pwntools](https://github.com/Gallopsled/pwntools)
* GDB + [Pwndbg](https://github.com/pwndbg/pwndbg) / GEF
* An LLM API Key (DeepSeek / OpenAI / Antigravity Setup)

## ⚡ Quick Start (Dev Mode)

```bash
# Clone the repository
git clone [https://github.com/Zenquiem/Dirge.git](https://github.com/Zenquiem/Dirge.git)

# Install dependencies
pip install -r requirements.txt

# Wake up the agent
python tools/banner.py
