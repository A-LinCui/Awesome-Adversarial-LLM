# Awesome-Adversarial-LLM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of the adversarial robustness of large language model related resources.

Please feel free to [pull requests](https://github.com/A-LinCui/Awesome-Adversarial-LLM/pulls) or [open an issue](https://github.com/A-LinCui/Awesome-Adversarial-LLM/issues) to add papers.

---

# Paper List

##  Abbreviations

### Modality
The modality in which the adversary conducts the attack.

- **T**: Text-only. Attack the model only through carefully designed input text.
- **V**: Vision-only. Attack the model only through carefully designed visual input.
- **A**: Text-and-vision. Attack the model in both text and visual modalities.

---

### Task
The task on which the experiments are conducted in the original paper. 

- **QA**: Question-Answering.
- **VQA**: Visual Question-Answering.
- **IC**: Image caption.
- **C**: General chat.

**Note:**
- Since a LLM can always accomplish a series of tasks, we only document the tasks in which experiments are conducted in the paper.
- The following tasks may overlap at some point.

---

### Adversarial knowledge
The knowledge of the adversary.

- **W**: White-box.
- **B**: Block-box.

**Note:**
- We categorize the transfer attack, generating adversarial examples on surrogate model(s) in a white-box manner, as a black-box one. 

---

### Adversarial goal
The goal of the adversary.

- **T**: Targeted attack.
- **U**: Untargeted attack.
- **J**: Jailbreak.

---

## 2023 Venues

| Title | Venue | Modality | Task | Knowledge | Goal | Code |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Generating Valid and Natural Adversarial Examples with Large Language Models](https://arxiv.org/abs/2311.11861)| - | T | QA | B | U | - |
|[Hijacking Large Language Models via Adversarial In-Context Learning](https://arxiv.org/abs/2311.09948)| - | T | QA | W | T/U | - |
| [An LLM can Fool Itself: A Prompt-Based Adversarial Attack](https://arxiv.org/pdf/2310.13345.pdf) | - | T | QA | B | T/U | [GitHub](https://github.com/GodXuxilie/PromptAttack) |
| [How Robust is Google's Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751) | - | V | IC | B | T/U/J | [GitHub](https://github.com/thu-ml/Attack-Bard) |
| [Image Hijacks: Adversarial Images can Control Generative Models at Runtime](https://arxiv.org/abs/2309.00236) | - | V | C | W | T/J | [GitHub](https://github.com/euanong/image-hijacks) | 
| [On the Adversarial Robustness of Multi-Modal Foundation Models](https://arxiv.org/abs/2308.10741) | ICCV | V | IC/VQA | W | T/U | - |
| [Are aligned neural networks adversarially aligned？](https://arxiv.org/abs/2306.15447)| - | V | IC | W | J | - |
| [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213) | - | T/V | C | W | J | [GitHub](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models) |
| [On Evaluating Adversarial Robustness of Large Vision-Language Models](https://arxiv.org/abs/2305.16934) | NeurIPS | V | IC/VQA | B | T | [GitHub](https://github.com/yunqing-me/AttackVLM) |
| [Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study](https://arxiv.org/abs/2305.13860) | - | T | C | B | J | - |
