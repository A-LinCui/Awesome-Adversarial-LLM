# Awesome-Adversarial-LLM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of the adversarial robustness of large language model related resources.

Please feel free to [pull requests](https://github.com/A-LinCui/Awesome-Adversarial-LLM/pulls) or [open an issue](https://github.com/A-LinCui/Awesome-Adversarial-LLM/issues) to add papers.

---

# Paper List

##  Abbreviations
| Modality | T | V | A |
|:--------:|:--------:|:--------:|:--------:|
| Explanation | Text-only | Vision-only | Text-Vision-Both | 

| Task | TC | IC | C | VQA |
|:--------:|:--------:|:--------:|:--------:|:--------:|
| Explanation | Text-Classification | Image Caption | General Chat | Visual Question-Answering |

| Knowledge | B | W |
|:--------:|:--------:|:--------:|
| Explanation | Block-box | White-Box |

| Goal | T | U | J |
|:--------:|:--------:|:--------:|:--------:|
| Explanation | Targeted | Untargeted | Jailbreak |

## 2023 Venues

| Title | Venue | Modality | Task | Knowledge | Goal | Code |
|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
|[Generating Valid and Natural Adversarial Examples with Large Language Models](https://arxiv.org/abs/2311.11861)| - | T | TC | B | U | - |
|[Hijacking Large Language Models via Adversarial In-Context Learning](https://arxiv.org/abs/2311.09948)| - | T | TC | W | T / U | - |
| [How Robust is Google's Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751) | - | V | IC | B | T / U / J | [GitHub](https://github.com/thu-ml/Attack-Bard) |
| [Are aligned neural networks adversarially aligned？](https://arxiv.org/abs/2306.15447)| - | V | IC | W | J | - |
| [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213) | - | T / V | C | W | J | [GitHub](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models) |
| [On Evaluating Adversarial Robustness of Large Vision-Language Models](https://arxiv.org/abs/2305.16934) | NeurIPS | V | IC / VQA | B | T | [GitHub]() |