---
title: 'Cut the Deadwood Out: Training-Free Backdoor Purification via Guided Module Substitution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Weijun Li
  - Xuanli He
  - Haolan Zhan
  - Qiongkai Xu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-02-20T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Findings of Association for Computational Linguistics EMNLP, 2025. <span style="color:red">**[Oral Presentation (Top ∼1.5% among submissions)]**</span>
publication_short: In Findings of Association for Computational Linguistics EMNLP 2025

abstract: "Model NLP models are commonly trained (or fine-tuned) on datasets from untrusted platforms like HuggingFace, posing significant risks of data poisoning attacks. A practical yet underexplored challenge arises when such backdoors are discovered after model deployment, making retraining-required defenses less desirable due to computational costs and data constraints. In this work, we propose Guided Module Substitution (GMS), an effective retraining-free method based on guided merging of the victim model with just a single proxy model. Unlike prior ad-hoc merging defenses, GMS uses a guided trade-off signal between utility and backdoor to selectively replaces modules in the victim model. GMS offers four desirable properties: (1) robustness to the choice and trustworthiness of the proxy model, (2) applicability under inaccurate data knowledge, (3) stability across hyperparameters, and (4) transferability across different attacks. Extensive experiments on encoder models and decoder LLMs demonstrate the strong effectiveness of GMS. GMS significantly outperforms even the strongest defense baseline, particularly against challenging attacks like LWS."

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: false

# # Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 2412.20476

# Custom links
links:
  - type: pdf
    url: https://arxiv.org/pdf/2412.20476
  - type: code
    url: https://github.com/weijun-l/guided-module-substitution
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

---