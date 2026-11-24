<p align="center">
  <img src="assets/scambranch-banner.png" alt="It's Not What the Scammer Says, It's How You Reply: Small Scam Detectors Judge Code-Mixed Fraud Calls by the Victim — AAAI-27 Student Abstract" width="100%">
</p>

# It's Not What the Scammer Says, It's How You Reply: Small Scam Detectors Judge Code-Mixed Fraud Calls by the Victim

![AAAI-27 Student Abstract](https://img.shields.io/badge/AAAI--27-Student%20Abstract-2f3640)
[![Dataset on HF](https://img.shields.io/badge/%F0%9F%A4%97%20Dataset-ScamBranch-yellow.svg)](https://huggingface.co/datasets/rishia2220/scambranch)
[![Adapters on HF](https://img.shields.io/badge/%F0%9F%A4%97%20Models-LoRA%20adapters-yellow.svg)](https://huggingface.co/rishia2220/scambranch-lora)

**Accepted to the AAAI-27 Student Abstract and Poster Program.**

Rishi Ahuja · Kumar Prateek · Simranjit Singh

Department of Information Technology, Dr. B. R. Ambedkar National Institute of Technology Jalandhar

[Dataset](https://huggingface.co/datasets/rishia2220/scambranch) · [LoRA adapters](https://huggingface.co/rishia2220/scambranch-lora)

---

## About the paper

Accuracy alone cannot tell whether a scam-call detector responds to what the caller asks or to how the person called reacts. **ScamBranch** contains **2,643 Romanized Hindi–, Tamil– and Telugu–English phone calls** from 60 scenario families, in which a fixed opening containing the caller's request branches into four replies: *cooperative*, *clarifying*, *resistant* and *suspicious*. Every scam has a genuine counterpart, and evidence and label are identical across branches, so any change in verdict comes from the reply. Across **16 open models with 135M–1.8B parameters**, one reply splits the verdicts of the 14 that answer validly in **30–80% of conversation sets**. Fine-tuning Qwen2.5-1.5B raises its macro-F1 from **0.73 to 0.86** and roughly halves these splits, yet scams in which the victim cooperates remain the hardest to catch.

All calls are synthetic, and every organisation, person and identifier in them is fictional. ScamBranch is released for defensive research on fraud detection only.

## Licence

Code: MIT ([LICENSE](LICENSE)). Data: research-only terms on the [dataset page](https://huggingface.co/datasets/rishia2220/scambranch). Adapters: Apache-2.0.

## Citation

```bibtex
@inproceedings{ahuja2027scambranch,
  title     = {It's Not What the Scammer Says, It's How You Reply: Small Scam Detectors Judge Code-Mixed Fraud Calls by the Victim},
  author    = {Ahuja, Rishi and Prateek, Kumar and Singh, Simranjit},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence (Student Abstract and Poster Program)},
  year      = {2027},
  note      = {Accepted for publication}
}
```
