# Draw Inevitability in Chess Under Perfect Play

**Dataset, code, and LaTeX source for the paper:**
*"Draw Inevitability in Chess Under Perfect Play: A Formal Conjecture and Theoretical Analysis"*
by **Nikolai Nedovodin** (2025)

---

## 📄 Overview

This repository contains all materials associated with the paper, including:

* **LaTeX source** of the full manuscript (`main.tex` and `references.bib`)
* **Figures** (TikZ/PGFPlots) and diagram sources
* **Python scripts** for empirical analysis
* **Dataset links** for 4 million engine self-play games
* **Reproducibility protocol** for falsifying or supporting the conjecture

The project presents:

* A **formal game-theoretic framework** for the draw inevitability conjecture
* The **Draw Stability Index (DSI)** metric
* Lemmas on **Repetition Safety** and **Fortress Basin Stability**
* A large-scale multi-engine dataset
* A reproducible falsifiability protocol

---

## 📂 Repository Structure

```
.
├── main.tex              # Main LaTeX file for the paper
├── references.bib        # Bibliography file
├── figures/              # TikZ/PGFPlots figure sources
├── scripts/              # Analysis scripts (Python)
├── data/                 # Placeholder for datasets (not tracked in Git)
├── results/              # Generated plots & processed results
├── .gitignore            # Ignore rules for LaTeX, Python, datasets
└── README.md             # This file
```

---

## 📊 Dataset

The **4-million-game self-play dataset** is too large to include in this repository.
It is hosted externally (link forthcoming) and contains:

* **Engines:** Stockfish 16 NNUE, Lc0 v0.30, Komodo Dragon 3
* **Time Control:** 10+0.1
* **Openings:** 500 ECO-coded positions
* **Adjudication:** Syzygy 7-man tablebases
* **Format:** PGN + JSON metadata

---

## 🛠 Installation

Clone the repository:

```
git clone https://github.com/cputer/chess-draw-conjecture.git
cd chess-draw-conjecture
```

If using Python scripts for analysis:

```
pip install -r requirements.txt
```

If compiling the paper:

```
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

---

## 📜 Citation

If you use this work, please cite:

```
@article{nedovodin2025draw,
  title={Draw Inevitability in Chess Under Perfect Play: A Formal Conjecture and Theoretical Analysis},
  author={Nikolai Nedovodin},
  year={2025},
  note={arXiv preprint (forthcoming)}
}
```

---

## 📬 Contact

**Author:** Nikolai Nedovodin
📧 **Email:** [info@cputer.com](mailto:info@cputer.com)

---

## 📄 License

All source code is released under the **MIT License**.
Figures, datasets, and text are released under **CC BY 4.0** unless otherwise stated.


