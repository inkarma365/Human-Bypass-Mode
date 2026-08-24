# Human Cognitive Asymmetry Engine (HCAE)

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Type](https://img.shields.io/badge/Type-Prompt_Engineering-blue)
![Target](https://img.shields.io/badge/Target-GPTZero%20%7C%20Turnitin%20%7C%20Originality.ai-red)
![Versions](https://img.shields.io/badge/Versions-2_Tiers-purple)

## 🧠 The Project
**HCAE** is a multi-tiered Prompt Engineering framework designed to bypass AI Detectors. Instead of using simple "spinner" logic (which just replaces synonyms but keeps the AI's mathematical DNA intact), this project forces Large Language Models to alter their **probabilistic generation architecture**.

As AI detectors have evolved from basic statistical analysis to deep syntactic tree evaluation, a single prompt approach is no longer sufficient. This repository contains two distinct generations of bypass methodologies.

---

## 📂 The Framework Tiers

### Tier 1: Cognitive Asymmetry Engine (Baseline)
**File:** [`Prompt-v1.md`](./Prompt-v1.md)

This prompt tackles the foundational metrics used by first and second-generation detectors: **Perplexity** (word predictability) and **Burstiness** (sentence length variation). 

**How it works:**
*   Forces the LLM to use "sub-optimal" vocabulary (choosing the 3rd most likely word instead of the 1st).
*   Destroys the standard Subject-Verb-Object rhythm.
*   Injects "Burstiness" by mathematically alternating very long, complex sentences with extremely short ones (3-5 words).
*   Uses conversational transitions instead of academic glue words (*Furthermore, Therefore*).

**Best for:** General content creation, blogs, older detection systems, and texts that need to sound highly conversational yet professional.

---

### Tier 2: Syntactic Topology Subversion (Advanced)
**File:** [`Prompt-v2.md`](./Prompt-v2.md)

Developed through reverse-engineering of next-generation detectors (like GPTZero v4+ and Turnitin's AI module), this prompt goes far beyond vocabulary and rhythm. It attacks the **structural logic** of AI generation.

**How it works:**
*   **Tree Asymmetry:** AI builds perfectly balanced sentence structures (symmetrical syntax trees). This prompt forces extreme left-branching or right-branching sentences, breaking the mathematical symmetry.
*   **Lexical Cohesion Eradication:** AI proves it's on topic by repeating the exact same root words (e.g., using "algorithm" 5 times in a paragraph). This prompt forces the use of semantic ties and abstract references ("this process", "the aforementioned framework") exactly like a human would.
*   **Information Density Clustering:** Instead of spreading facts evenly, it forces the AI to cram multiple data points into one massive sentence, followed by a low-information, tautological conclusion. This mimics human cognitive load.
*   **N-gram Disruption:** Actively breaks common trigrams and 4-grams that detectors use as AI fingerprints.

**Best for:** Strict academic writing, technical documentation, university submissions, and bypassing the most aggressive modern AI detectors.

---

## 🚀 Why Not Use Traditional Spinners (Quillbot, WordAI)?

Traditional paraphrasers swap words but leave the AI's **syntactic skeleton** untouched. Modern detectors analyze the shape of the sentence, not just the words. If the skeleton is perfectly symmetrical, the text is flagged as AI, regardless of the vocabulary used. 

HCAE forces the LLM to generate a deformed, asymmetrical skeleton from the very first token, making it mathematically indistinguishable from human writing.

## 🛠️ How To Use

1. Clone or download this repository.
2. Choose your tier:
   * Use **[`Prompt-v1.md`](./Prompt-v1.md)** for general, conversational humanization.
   * Use **[`Prompt-v2.md`](./Prompt-v2.md)** for strict, technical, or academic humanization.
3. Open the file and copy the entire System Prompt.
4. Paste it as a system instruction (or as the first message) in ChatGPT, Claude, or any LLM.
5. Paste the AI-generated text you want to rewrite immediately after the prompt.

## 📌 Important Notes
*   **Data Integrity:** Both prompts are strictly instructed *never* to alter, approximate, or hallucinate numbers, names, or technical data. The meaning remains 100% intact; only the syntax changes.
*   **Plain Text:** Both prompts include instructions to strip special characters/diacritics to ensure clean ASCII output if required.

## 📄 License
This project is open-source and released under the MIT License. Feel free to adapt the prompts to your specific linguistic or structural needs.


*Disclaimer: This project is intended for educational purposes to demonstrate the flaws and biases in automated AI detection algorithms. It should be used to humanize assistively generated drafts, not to facilitate academic plagiarism.*
