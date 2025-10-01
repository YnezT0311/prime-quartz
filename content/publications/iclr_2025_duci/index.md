---
title: 'How much of my dataset did you use? Quantitative Data Usage Inference in Machine Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jiayuan Ye
  - Sajjad Zarifzadeh
  - Reza Shokri

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-09-20T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Internatinal Conference of Learning Representations*, 2025. <span style="color:red">**[Oral Presentation (Top ∼1.5% among submissions)]**</span>
publication_short: In *ICLR 2025* <span style="color:red">**[Oral Presentation (Top ∼1.5% among submissions)]**</span>

abstract: "How much of a given dataset was used to train a machine learning model? This is a critical question for data owners assessing the risk of unauthorized data usage and protecting their right (United States Code, 1976). However, previous work mistakenly treats this as a binary problem—inferring whether all or none or any or none of the data was used—which is fragile when faced with real, non-binary data usage risks. To address this, we propose a fine-grained analysis called Dataset Usage Cardinality Inference (DUCI), which estimates the exact proportion of data used. Our algorithm, leveraging debiased membership guesses, matches the performance of the optimal MLE approach (with a maximum error <0.1) but with significantly lower (e.g., $300 \times$ less) computational cost."


# Display this page in the Featured widget?
featured: false

# # Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://openreview.net/forum?id=EUSkm2sVJ6"
  - type: code
    url: https://github.com/YnezT0311/project_dataset_usage_inference
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  - type: video
    url: https://iclr.cc/virtual/2025/session/31960


---