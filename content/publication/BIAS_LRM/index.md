---
title: "Is Reasoning What You Need to Mitigate Bias? A Study of Adversarial Robustness to Bias Elicitation in Large Reasoning Models"

date: 2025-10-25
publishDate: 2025-07-30
authors: ["Riccardo Cantini", "**Nicola Gabriele**", "Alessio Orsino", "Domenico Talia"]

abstract: "Reasoning Language Models (RLMs) have gained traction for their ability to perform complex, multi-step reasoning tasks through mechanisms such as Chain-of-Thought (CoT) prompting or fine-tuned reasoning traces. While these capabilities promise improved reliability, their impact on robustness to social biases remains unclear. In this work, we leverage the CLEAR-Bias benchmark, originally designed for Large Language Models (LLMs), to investigate the adversarial robustness of RLMs to bias elicitation. We systematically evaluate state-of-the-art RLMs across diverse sociocultural dimensions, using an LLM-as-a-judge approach for automated safety scoring and leveraging jailbreak techniques to assess the strength of built-in safety mechanisms. Our evaluation addresses three key questions: *i* how the introduction of reasoning capabilities affects model fairness and robustness; *ii* whether models fine-tuned for reasoning exhibit greater safety than those relying on CoT prompting at inference time; and *iii* how the success rate of jailbreak attacks targeting bias elicitation varies with the reasoning mechanisms employed. Our findings reveal a nuanced relationship between reasoning capabilities and bias safety. Surprisingly, models with explicit reasoning, whether via CoT prompting or fine-tuned reasoning traces, are generally more vulnerable to bias elicitation than base models without such mechanisms, suggesting reasoning may unintentionally open new pathways for stereotype reinforcement. Reasoning-enabled models appear somewhat safer than those relying on CoT prompting, which are particularly prone to contextual reframing attacks through storytelling prompts, fictional personas, or reward-shaped instructions. These results challenge the assumption that reasoning inherently improves robustness and underscore the need for more bias-aware approaches to reasoning design."

featured: false
publication: "AEQUITAS 2025"
# url_pdf:
# doi:


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false


tags: [ "Reasoning Language Models", "Large Language Models", "Small Language Models", "Bias", "Stereotype", "Jailbreak", "Adversarial Robustness", "Fairness", "Sustainable AI"]

---
