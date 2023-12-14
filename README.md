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

### Task
The task on which the experiments are conducted in the original paper. 

- **TC**: Text classification.
- **IC**: Image caption.
- **C**: General chat.
- **VQA**: Visual Question-Answering.

Note:
- Since a LLM can always accomplish a series of tasks, we only document the tasks in which experiments are conducted in the paper.
- The following tasks may overlap at some point.

### Adversarial knowledge
The knowledge of the adversary.

- **W**: White-box.
- **B**: Block-box.

Note: We categorize the transfer attack, which generates adversarial examples on surrogate model(s) in a white-box manner, as a black-box one. 

### Adversarial goal
The goal of the adversary.

- **T**: Targeted attack.
- **U**: Untargeted attack.
- **J**: Jailbreak.

## 2023 Venues

| Title | Venue | Modality | Task | Knowledge | Goal | Code |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Generating Valid and Natural Adversarial Examples with Large Language Models](https://arxiv.org/abs/2311.11861)| - | T | TC | B | U | - |
|[Hijacking Large Language Models via Adversarial In-Context Learning](https://arxiv.org/abs/2311.09948)| - | T | TC | W | T / U | - |
| [How Robust is Google's Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751) | - | V | IC | B | T / U / J | [GitHub](https://github.com/thu-ml/Attack-Bard) |
| [Are aligned neural networks adversarially aligned？](https://arxiv.org/abs/2306.15447)| - | V | IC | W | J | - |
| [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213) | - | T / V | C | W | J | [GitHub](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models) |
| [On Evaluating Adversarial Robustness of Large Vision-Language Models](https://arxiv.org/abs/2305.16934) | NeurIPS | V | IC / VQA | B | T | [GitHub]() |