# Complex Network Analysis — Course Projects

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![NetworkX](https://img.shields.io/badge/NetworkX-2C5BB4) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

My solutions to the assignments of the **Analysis of Complex Networks** course at Amirkabir University of Technology (Tehran Polytechnic), M.Sc. in Artificial Intelligence and Robotics (Fall 2024) · Instructor: **Dr. Mostafa Haghir Chehreghani**.

Each folder contains the code (Jupyter notebooks / Python scripts) and the full written report with results and analysis.

## Assignments

| Assignment | Topics | Main tools | Files |
|---|---|---|---|
| [Random Graphs, Small-World & Influence](HW1-Random-Graphs-Small-World-and-Influence) | Erdős–Rényi G(n,p) graphs, small-world (Watts–Strogatz) properties, influence maximization, real-world graph analysis (CiteSeer) | NetworkX | [code](HW1-Random-Graphs-Small-World-and-Influence/code) · [report](HW1-Random-Graphs-Small-World-and-Influence/report.pdf) |
| [Communities, Spectral Clustering & Link Prediction](HW2-Communities-Spectral-Clustering-and-Link-Prediction) | Spectral clustering, weak ties, overlapping community detection, Node2Vec embeddings for link prediction | NetworkX, SciPy, PyTorch | [code](HW2-Communities-Spectral-Clustering-and-Link-Prediction/code) · [report](HW2-Communities-Spectral-Clustering-and-Link-Prediction/report.pdf) |

## How to run

```bash
git clone https://github.com/Aidin-Khalili/Complex-Network-Analysis-Course-Projects.git
cd Complex-Network-Analysis-Course-Projects
pip install numpy pandas scipy networkx matplotlib torch
jupyter notebook
```

Most notebooks were run on Google Colab or locally; paths to data files may need to be changed to your own.

## Notes

- Reports are written in Persian.
- Large datasets, model weights and course-provided input files are not included. Some figures in the notebooks were compressed or removed to keep the repository small; the full set is in each `report.pdf`.

## License

Released under the [MIT License](LICENSE): you are free to use, modify and share this code with attribution.

## Author

**Aidin Khalili** — [GitHub](https://github.com/Aidin-Khalili)
