<p align="center">
  <img src="https://img.shields.io/badge/awesome-RS--CD-purple" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" />
</p>
<h1 align="center">
  Foundation Models for Remote Sensing Change Detection: A Comprehensive Survey
</h1>
<p align="center">
  <a href="https://scholar.google.com/"><b>Kaixuan Jiang</b></a> ·
  <a href="https://scholar.google.com/"><b>Chen Wu<b>*</a> 📧·
  <a href="https://scholar.google.com/"><b>Liangpei Zhang<b></a>·
  <a href="https://scholar.google.com/"><b>Bo Du<b></a>·
  <a href="https://scholar.google.com/"><b>Haonan Guo</b></a> ·
  <a href="https://scholar.google.com/"><b>Di Wang<b></a> ·
  <a href="https://scholar.google.com/"><b>Zhenghui Zhao<b></a>·
  <a href="https://scholar.google.com/"><b>Jialu Li<b></a>·
  <a href="https://scholar.google.com/"><b>Xiaolei Qin</b></a> ·
  <a href="https://scholar.google.com/"><b>Yao Jin<b></a> ·
  <a href="https://scholar.google.com/"><b>Wen Zhou<b></a>·
  <a href="https://scholar.google.com/"><b>Chengxi Han<b></a>·
  <a href="https://scholar.google.com/"><b>Hongruixuan Chen</b></a> ·
  <a href="https://scholar.google.com/"><b>Meiqi Hu<b></a> ·
  <a href="https://scholar.google.com/"><b>Zhuo Zheng<b></a>·
  <a href="https://scholar.google.com/"><b>Jia Liu<b></a>·
  <a href="https://scholar.google.com/"><b>Tongfei Liu<b></a> ·
  <a href="https://scholar.google.com/"><b>Lei Ding<b></a>·
  <a href="https://scholar.google.com/"><b>Kaiyu Li<b></a>·
  <a href="https://scholar.google.com/"><b>Xiangyong Cao</b></a>
</p>
<p align="center">
  <a href="https://ieeexplore.ieee.org/">
    <img src="https://img.shields.io/badge/IEEE-XXX-blue">
  </a>
  <a href="https://arxiv.org/">
    <img src="https://img.shields.io/badge/arXiv-PDF-green">
  </a>
</p>




This repository records and tracks recent **Foundation Model-based Remote Sensing Change Detection (FM4CD)** methods. If you find any missing work or have suggestions (papers, implementations, or other resources), feel free to open an issue or submit a pull request.

---

⭐ **Star this repo**⭐

If you find this repository helpful, please consider giving it a ⭐.  We will continue updating the latest progress in this field.



 📢 **Add Your Paper to Our Survey**!

- You are welcome to open an issue or PR for your **FM4CD** work!!!
- We will include it in the next update of our survey.
- The repository is under active updating 🥳🔥🔥🔥  

✨ **Highlight**!!
✅ The first comprehensive survey on **Foundation Models for Remote Sensing Change Detection**.

✅ Public datasets, benchmark results, and code links are provided.

✅ We will **continue tracking related work** and keep this repository updated.



 📖 **Introduction**

---

Timeline of FM4CD:

![Overview](F:\Githubcode\FM4CD\fig\2.jpg)



🧩 **Remote Sensing Change Detection with Vision Foundation Models**

| Time | Model           | Paper Title                                   | VFM Backbone | Strategy                                    | Code |
| ---- | --------------- | --------------------------------------------- | ------------ | ------------------------------------------- | ---- |
| 2023 | SAM-CD (Al-Tam) | SAM-CD: Segment Anything for Change Detection | SAM          | Frozen encoder + lightweight change module  | ✗    |
| 2023 | DINO-S          | DINO-S for Remote Sensing Change Detection    | DINO         | Frozen backbone + Adapter interaction       | ✗    |
| 2024 | SAM-CD (Ding)   | FastSAM-based Change Detection                | FastSAM      | Bi-temporal feature fusion + PEFT           | ✔    |
| 2024 | BAN-BIT         | Boundary-Aware Network with SAM               | SAM          | Cross-temporal fusion + Decoder redesign    | ✔    |
| 2024 | RSBuilding      | RSBuilding-CD                                 | SAM          | Multi-scale feature interaction             | ✔    |
| 2025 | ChangeSAM       | ChangeSAM: RS-LoRA based SAM-CD               | SAM          | LoRA + Spatial Prompting                    | ✔    |
| 2025 | SAM-CEM-CD      | Cross-Enhancement Modeling with FastSAM       | FastSAM      | Multi-scale difference modeling             | ✔    |
| 2025 | RFHP-CD         | Prompt-driven HyperSIGMA CD                   | HyperSIGMA   | RS-specific FM + Hierarchical Prompt Tuning | ✗    |
| 2025 | PeftCD          | Parameter-efficient Fine-tuning for CD        | SAM + DINO   | Adapter + LoRA                              | ✔    |

| ........
