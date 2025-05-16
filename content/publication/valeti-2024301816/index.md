---
title: 'GBKPA and AuxShield: Addressing adversarial robustness and transferability
  in android malware detection'
authors:
- Kumarakrishna Valeti
- Hemant Rathore
date: '2024-01-01'
publishDate: '2025-05-16T04:34:47.901376Z'
publication_types:
- article-journal
publication: '*Forensic Science International: Digital Investigation*'
doi: https://doi.org/10.1016/j.fsidi.2024.301816
abstract: Android stands as the predominant operating system within the mobile ecosystem.
  Users can download applications from official sources like Google Play Store and
  other third-party platforms. However, malicious actors can attempt to compromise
  user device integrity through malicious applications. Traditionally, signatures,
  rules, and other methods have been employed to detect malware attacks and protect
  device integrity. However, the growing number and complexity of malicious applications
  have prompted the exploration of newer techniques like machine learning (ML) and
  deep learning (DL). Many recent studies have demonstrated promising results in detecting
  malicious applications using ML and DL solutions. However, research in other fields,
  such as computer vision, has shown that ML and DL solutions are vulnerable to targeted
  adversarial attacks. Malicious actors can develop malicious adversarial applications
  that can bypass ML and DL based anti-viruses. The study of adversarial techniques
  related to malware detection has now captured the security community’s attention.
  In this work, we utilise android permissions and intents to construct 28 distinct
  malware detection models using 14 classification algorithms. Later, we introduce
  a novel targeted false-negative evasion attack, Gradient Based K Perturbation Attack
  (GBKPA), designed for grey-box knowledge scenarios to assess the robustness of these
  models. The GBKPA attempts to craft malicious adversarial samples by making minimal
  perturbations without violating the syntactic and functional structure of the application.
  GBKPA achieved an average fooling rate (FR) of 77 % with only five perturbations
  across the 28 detection models. Additionally, we identified the most vulnerable
  android permissions and intents that malicious actors can exploit for evasion attacks.
  Furthermore, we analyse the transferability of adversarial samples across different
  classes of models and provide explanations for the same. Finally, we proposed AuxShield
  defence mechanism to develop robust detection models. AuxShield reduced the average
  FR to 3.25 % against 28 detection models. Our findings underscore the need to understand
  the causation of adversarial samples, their transferability, and robust defence
  strategies before deploying ML and DL solutions in the real world.
tags:
- Android
- Deep learning
- Malware
- Machine learning
- Robustness
- Transferability
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S2666281724001409
---
