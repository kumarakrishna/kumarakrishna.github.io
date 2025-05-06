---
title: 'DNN-GRAD: Exploiting Membership Inference for Adversarial Attacks on Malware Detection Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hemant Rathore

date: '2013-07-01T00:00:00Z'
doi: '10.1109/CCNC54725.2025.10975992'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 IEEE 22nd Consumer Communications & Networking Conference (CCNC)*
publication_short: In *IEEE CCNC 2025*

abstract: Android is currently the most dominant mobile operating system, with over 70 % of smartphones using it. This widespread adoption makes malware developers target Android devices to exploit security vulnerabilities. Current mal ware de-tection solutions use a combination of traditional signature and heuristics-based methods along with newer machine learning-based methods for protection against evolving malware attacks. While effective, machine learning models are often vulnerable to adversarial attacks. Adversaries can carefully perturb malware samples to evade detection by these models. Furthermore, these models are known to leak information about their training data, which adversaries can exploit to infer private and sensitive information via membership inference attacks. In this study, we propose a novel method to exploit membership information to improve the effectiveness of adversarial attacks. This method effectively selects a subset of available data using membership information leaked from the target model, allowing one to better approximate the target model's training data. Training a local model with the selected data, we demonstrate that an attacker can improve the effectiveness of the attack, achieving a 17 % increase in fooling rate while using 15 % less data compared to using all available data. We then propose DNN-GRAD, a grey-box gradient-based adversarial attack which, by using this leaked membership information, achieves a fooling rate of 56.69 % against various machine learning-based malware detectors. We also demonstrate that a combination of defences like adversarial training and regularization reduces the fooling rate by 46 % reduction in fooling rate across various model architectures.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
