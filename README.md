<table>
<tr><td valign="top" width="58%">

### Yichen Chen 👋

I'm a master's student at **Tianjin University**, where I spend most of my time at the intersection of three things that don't always play nicely together — text, vision, and audio in large models.

Lately, that means writing small training libraries to glue frozen encoders to language backbones, building benchmarks for whichever new thing the field has decided to disagree about, and quietly suspecting that most VLMs are just very confident text models with a picture stapled to the side.

I like writing open-source tools that I'd actually want to use, and I dislike repos that ship a single `train.py` with 47 hardcoded paths in it.

#### Currently

- 🎙️ Comparing speech tokenizers head-to-head — neural codecs vs SSL units
- 🧪 Probing what VLMs actually encode at each layer (mostly: less than you'd hope)
- 🧰 Maintaining a small joint text+vision+audio training loop
- ☕ Surviving thesis-writing season on coffee and stubbornness

</td><td valign="top" width="42%">

#### Affiliation

| | |
|---|---|
| 🎓 | MSc @ Tianjin University |
| 🔬 | Multimodal / Speech / Vision LLMs |
| 📍 | Tianjin, China |
| ✍️ | (occasionally on arXiv) |

#### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HF](https://img.shields.io/badge/🤗_HF-FFD21E?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

</td></tr>
</table>

---

#### Selected projects

| Project | What it's for |
|---|---|
| [**uni-mm-trainer**](https://github.com/bandyah/uni-mm-trainer) | A small training library for multimodal LLMs that combine at least two of text / vision / audio. Q-Former, Resampler, LoRA, the usual suspects — without the dependency sprawl. |
| [**speech-tokenizer-arena**](https://github.com/bandyah/speech-tokenizer-arena) | Head-to-head benchmark for discrete and continuous speech tokenizers across eight evaluation axes. The leaderboard is the point. |
| [**vlm-probe-suite**](https://github.com/bandyah/vlm-probe-suite) | Diagnostic probes for vision-language models: object presence, spatial relations, color, counting, attribute binding — with selectivity controls and modality attribution. |

#### Research interests

`Multimodal LLMs` &nbsp; · &nbsp; `Speech Tokenization & Codecs` &nbsp; · &nbsp; `Vision-Language Alignment` &nbsp; · &nbsp; `Probing & Interpretability` &nbsp; · &nbsp; `Efficient Adapter Methods`

<details>
<summary>📝 Things I'd write a paper about if I had time</summary>

- A proper unified evaluation for speech tokenizers used in speech LLMs (current papers all measure different things on different data)
- What changes inside a frozen LLM when you bolt on a vision encoder via LoRA — measured per layer rather than as a global score
- Whether modality adapters are doing real cross-modal binding or just very expensive feature averaging

</details>
