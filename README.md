# Do You Hear What I Mean? — Project Page

[![Paper](https://img.shields.io/badge/IEEE-ICASSP%202026-00629B?logo=ieee&logoColor=white)](https://doi.org/10.1109/ICASSP55912.2026.11462935)
[![arXiv](https://img.shields.io/badge/arXiv-2509.13989-B31B1B?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.13989)
[![Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-E--VOC-FFD21E)](https://huggingface.co/datasets/wizzzzzzzzz/E-VOC)
[![Website](https://img.shields.io/badge/Project%20Page-live-1f6feb)](https://huangchengchou.com/Do-You-Hear-What-I-Mean/)

Project page for:

> Yi-Cheng Lin, Huang-Cheng Chou, Tzu-Chieh Wei, Kuan-Yu Chen, Hung-yi Lee,
> **"Do You Hear What I Mean? Quantifying the Instruction-Perception Gap in
> Instruction-Guided Expressive Text-to-Speech Systems,"** *IEEE ICASSP*, 2026.

**Live page:** https://huangchengchou.com/Do-You-Hear-What-I-Mean/

## TL;DR

You can prompt an instruction-guided TTS system to "sound excited" — but does a
listener actually hear excitement? We measure the gap between the style
instruction given to five modern ITTS systems and what human listeners perceive,
across four expressive dimensions (adverbs of degree, graded emotion intensity,
speaker age, word-level emphasis) and three acoustic dimensions.

Key findings:

1. **gpt-4o-mini-tts aligns best** between instruction and perceived output
   across acoustic dimensions.
2. All five systems **default to adult-sounding voices**, even when asked for
   child or elderly speakers.
3. **Fine-grained control remains unsolved**: slightly different attribute
   instructions are often indistinguishable in the generated speech.

## E-VOC corpus

The **Expressive VOice Control (E-VOC)** corpus released with the paper contains
large-scale human ratings of synthesized speech from five ITTS systems:
[wizzzzzzzzz/E-VOC](https://huggingface.co/datasets/wizzzzzzzzz/E-VOC)
(companion audio: [wizzzzzzzzz/TTS_audio](https://huggingface.co/datasets/wizzzzzzzzz/TTS_audio)).

## Citation

```bibtex
@inproceedings{lin2026you,
  title        = {{Do You Hear What I Mean? Quantifying the Instruction-Perception Gap in Instruction-Guided Expressive Text-to-Speech Systems}},
  author       = {Lin, Yi-Cheng and Chou, Huang-Cheng and Wei, Tzu-Chieh and Chen, Kuan-Yu and Lee, Hung-yi},
  booktitle    = {IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages        = {16472--16476},
  year         = {2026},
  organization = {IEEE},
  doi          = {10.1109/ICASSP55912.2026.11462935}
}
```

## Acknowledgements

This page is adapted from the
[Nerfies](https://github.com/nerfies/nerfies.github.io) project page template
and, like the template, is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
