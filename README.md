# README.md


# Human Cognitive Asymmetry Engine (HCAE)

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Type](https://img.shields.io/badge/Type-Prompt_Engineering-blue)
![Target](https://img.shields.io/badge/Target-GPTZero%20%7C%20Turnitin%20%7C%20Originality.ai-red)

## 🧠 The Project
**HCAE** is a Prompt Engineering framework designed to bypass AI Detectors not by superficially altering words (like traditional spinners), but by modifying the **probabilistic architecture** of the text.

Most anti-AI tools (GPTZero, Turnitin, Copyleaks) do not "read" for meaning; they analyze two mathematical metrics:
1. **Perplexity (Unpredictability):** How predictable the next word choice is. AI always selects the highest probability word (Top-1). Humans naturally select lower-probability words (Top-3 or Top-5).
2. **Burstiness (Rhythm):** The variation in sentence length and structure. AI writes homogeneous sentences (15-20 words). Humans alternate long, complex sentences with very short fragments.

## ⚙️ How It Works (The Methodology)
Instead of simply asking an LLM to "write like a human" (which results in fake, easily detectable slang), HCAE imposes strict syntactic rules that break the model's mathematical patterns.

The process relies on 5 pillars:

1. **SVO Pattern Disruption:** Deliberately moving dependent clauses to the beginning of sentences to eliminate the monotonous Subject-Verb-Object structure typical of AI.
2. **Burstiness Injection:** Mathematically forcing the alternation between highly complex sentences (multiple clauses) and "chopped" sentences (max 6 words).
3. **Perplexity Elevation:** Absolute prohibition of high-probability connectors (*Furthermore, Moreover, However, Therefore*) and forcing the use of sub-optimal lemmas (the model's second or third word choice).
4. **Parallelism Destruction:** Transforming logical bullet points into asymmetric discursive paragraphs. Technical data is woven into the text, not listed.
5. **Academic Micro-Colloquialisms:** Inserting acceptable "human cracks" in a formal context (e.g., *"To be fair"*, *"Nobody denies that"*), simulating the cognitive load of a student or researcher explaining a complex concept.

## 🚀 Why Not Use Simple Spinners (Quillbot, WordAI)?
Paraphrasers replace synonyms but leave the AI's perfect-pattern syntax completely intact. Modern detectors will analyze the sentence structure and still classify it as "AI-generated." HCAE acts at the level of *syntactic generation*, making the text mathematically human from the ground up.

## 🛠️ How To Use This Repo
1. Clone or download this repository.
2. Open the `prompt.md` file.
3. Copy the System Prompt contained inside.
4. Paste it as a system instruction (or as the first message) in ChatGPT, Claude, or any other LLM.
5. Paste the text you want to rewrite immediately after the prompt.

## 📌 Ideal Use Cases
- Academic publishing and university seminars.
- Content Marketing and SEO (where search engines penalize AI-spun content).
- Professional email writing.
- Technical documentation requiring a "human" tone.

## 📄 License
This project is open-source and released under the MIT License. Feel free to adapt the prompt to your specific linguistic needs.

---
*Disclaimer: Using this tool for academic fraud (e.g., stealing others' work) goes against the ethics of this project. The purpose is to demonstrate the flaws in current AI detectors and to allow human creators to clean up assistively generated drafts.*
```
**INPUT TEXT TO REWRITE:**
[PASTE YOUR TEXT HERE]
```
