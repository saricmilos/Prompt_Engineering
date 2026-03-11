# 🧠 Prompt Engineering

A structured, hands-on curriculum for mastering prompt engineering — from foundational concepts to advanced multi-step systems, evaluation, and safety. Each phase builds on the last, taking you from writing your first prompt to designing production-ready pipelines.

---

## 📚 Curriculum Overview

| Phase | Days | Theme |
|-------|------|-------|
| [Phase 1](#-phase-1-the-foundations-days-12) | 1–2 | Core mechanics & instruction structure |
| [Phase 2](#-phase-2-core-learning-paradigms-day-3) | 3 | Zero-shot, few-shot & role prompting |
| [Phase 3](#-phase-3-reasoning--logic-day-4) | 4 | Chain-of-thought & complex reasoning |
| [Phase 4](#-phase-4-advanced-workflow--automation-days-56) | 5–6 | Chaining, templates & optimization |
| [Phase 5](#-phase-5-evaluation--safety-day-7) | 7 | Evaluation, security & ethics |

---

## 🗂️ Phase 1: The Foundations (Days 1–2)

> Focus on the core mechanics of how models interpret instructions.

### Day 1 — Intro & Structure
| Notebook | Description |
|----------|-------------|
| `intro-prompt-engineering-lesson.ipynb` | What prompt engineering is and why it matters |
| `basic-prompt-structures.ipynb` | Anatomy of a well-formed prompt |
| `prompt-formatting-structure.ipynb` | How formatting affects model output |
| `instruction-engineering-notebook.ipynb` | Writing clear, actionable instructions |

### Day 2 — Specificity & Constraints
| Notebook | Description |
|----------|-------------|
| `ambiguity-clarity.ipynb` | Identifying and eliminating vague language |
| `negative-prompting.ipynb` | Telling the model what *not* to do |
| `constrained-guided-generation.ipynb` | Controlling output format and scope |
| `prompt-length-complexity-management.ipynb` | Balancing detail without overloading the context |

---

## 🎯 Phase 2: Core Learning Paradigms (Day 3)

> Learn the three primary ways to prime a model for a task.

### Day 3 — The "Shots" & Roles
| Notebook | Description |
|----------|-------------|
| `zero-shot-prompting.ipynb` | Getting results with no examples |
| `few-shot-learning.ipynb` | Guiding the model with in-context examples |
| `role-prompting.ipynb` | Assigning personas and expert roles |
| `specific-task-prompts.ipynb` | Tailoring prompts for domain-specific tasks |

---

## 🔗 Phase 3: Reasoning & Logic (Day 4)

> Move from simple queries to complex, multi-step problem-solving.

### Day 4 — Thinking it Through
| Notebook | Description |
|----------|-------------|
| `cot-prompting.ipynb` | Chain-of-Thought: making models show their work |
| `self-consistency.ipynb` | Sampling multiple reasoning paths for reliability |
| `task-decomposition-prompts.ipynb` | Breaking hard problems into manageable steps |

---

## ⚙️ Phase 4: Advanced Workflow & Automation (Days 5–6)

> Move beyond single prompts into multi-step systems.

### Day 5 — Chaining & Templates
| Notebook | Description |
|----------|-------------|
| `prompt-chaining-sequencing.ipynb` | Connecting prompts where each output feeds the next |
| `prompt-templates-variables-jinja2.ipynb` | Dynamic, reusable prompts with Jinja2 templating |

### Day 6 — Optimization & Multilingual
| Notebook | Description |
|----------|-------------|
| `prompt-optimization-techniques.ipynb` | Systematic approaches to improving prompt performance |
| `multilingual-prompting.ipynb` | Prompting effectively across languages |

---

## 🛡️ Phase 5: Evaluation & Safety (Day 7)

> The professional layer — ensuring your prompts are safe, ethical, and measurable.

### Day 7 — The Guardrails
| Notebook | Description |
|----------|-------------|
| `evaluating-prompt-effectiveness.ipynb` | Metrics and frameworks for measuring prompt quality |
| `prompt-security-and-safety.ipynb` | Defending against prompt injection and adversarial inputs |
| `ethical-prompt-engineering.ipynb` | Bias, fairness, and responsible AI principles |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab
- An API key for your LLM of choice (OpenAI, Anthropic, etc.)

### Installation

```bash
# Clone the repository
git clone https://github.com/saricmilos/Prompt_Engineering.git
cd Prompt_Engineering

# Install dependencies
pip install -r requirements.txt
```

### Environment Setup

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_key_here
HUGGINFACE_API_KEY=your_key_here
```

---

## 📁 Repository Structure

```
prompt-engineering/
├── phase-1-foundations/
│   ├── intro-prompt-engineering-lesson.ipynb
│   ├── basic-prompt-structures.ipynb
│   ├── prompt-formatting-structure.ipynb
│   └── instruction-engineering-notebook.ipynb
├── phase-2-learning-paradigms/
│   ├── zero-shot-prompting.ipynb
│   ├── few-shot-learning.ipynb
│   ├── role-prompting.ipynb
│   └── specific-task-prompts.ipynb
├── phase-3-reasoning/
│   ├── cot-prompting.ipynb
│   ├── self-consistency.ipynb
│   └── task-decomposition-prompts.ipynb
├── phase-4-advanced/
│   ├── prompt-chaining-sequencing.ipynb
│   ├── prompt-templates-variables-jinja2.ipynb
│   ├── prompt-optimization-techniques.ipynb
│   └── multilingual-prompting.ipynb
├── phase-5-evaluation-safety/
│   ├── evaluating-prompt-effectiveness.ipynb
│   ├── prompt-security-and-safety.ipynb
│   └── ethical-prompt-engineering.ipynb
├── requirements.txt
└── README.md
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.