# Streaming SSL Graph Smart-Grid Anomaly Detection

Source notebook and reproducibility materials for **evidence-aware streaming anomaly detection in cyber-physical smart grids using self-supervised graph learning**.

This repository supports the manuscript:

**Streaming Self-Supervised Graph Learning for Evidence-Aware Anomaly Detection in Cyber–Physical Smart Grids**

## Repository contents

```text
.
├── README.md
├── LICENSE
├── requirements.txt
├── notebooks/
│   └── Grid007_reviewer_context_aware_v9.ipynb
├── outputs/
│   └── selected figures, tables, and result summaries
└── supplementary/
    └── additional small supporting files
```

Large generated files, full output archives, model checkpoints, and raw data should not be committed directly to Git. They may be shared separately through a GitHub Release asset or as journal supplementary material.

## Main notebook

The main reproducibility notebook is:

```text
notebooks/Grid007_reviewer_context_aware_v9.ipynb
```

The notebook contains the experimental workflow for the reviewer-context-aware smart-grid anomaly detection pipeline, including stream construction, anomaly injection, self-supervised graph learning, evidence-aware alerting, and result generation.

## Environment setup

Create and activate a Python environment, then install dependencies:

```bash
pip install -r requirements.txt
```

A typical `requirements.txt` may include:

```text
numpy
pandas
matplotlib
scikit-learn
torch
torch-geometric
networkx
tqdm
jupyter
notebook
```

Depending on the runtime environment, PyTorch and PyTorch Geometric may require installation commands specific to the CUDA/Python version. See the official PyTorch and PyTorch Geometric installation instructions if GPU-specific installation is needed.

## How to run

1. Clone the repository:

```bash
git clone https://github.com/mshahidbhatti/streaming-ssl-graph-smart-grid-anomaly-detection.git
cd streaming-ssl-graph-smart-grid-anomaly-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/Grid007_reviewer_context_aware_v9.ipynb
```

4. Run the cells sequentially.

The notebook may also be executed in Google Colab or VS Code with a compatible Python environment.

## Data and output availability

This repository is intended to provide source code and reproducibility materials. Large raw datasets, generated output folders, trained model checkpoints, and complete ZIP archives are not tracked directly in Git to avoid repository-size and binary-file limitations.

If a complete output archive is required, it can be provided separately as:

- a GitHub Release asset, or
- a supplementary ZIP file in the journal submission system.

Suggested statement:

```text
The source notebook and reproducibility files are available in this GitHub repository. The complete output archive is provided separately as supplementary material or as a GitHub Release asset. Large generated files are not tracked directly in Git.
```

## Reproducibility notes

For reproducibility, please report or preserve the following when sharing results:

- Python version
- PyTorch version
- PyTorch Geometric version
- CUDA/GPU configuration, if used
- random seed values
- notebook version
- output ZIP or release version

## License

The source code and reproducibility notebook are released under the MIT License.

Manuscript text, figures, third-party datasets, and externally sourced materials remain subject to their respective copyright and licensing terms.

## Citation

If you use this repository, please cite the associated manuscript:

```bibtex
@article{abedin2026streaming,
  title   = {Streaming Self-Supervised Graph Learning for Evidence-Aware Anomaly Detection in Cyber-Physical Smart Grids},
  author  = {Abedin, Zain Ul and Jianbin, Li and Waqar, Ali and Shahid, Muhammad and Pervaiz, Sunil and Sohail, Abid},
  journal = {Submitted manuscript},
  year    = {2026}
}
```

## Contact

For questions about the repository, please contact:

**Muhammad Shahid Bhatti**  
GitHub: [mshahidbhatti](https://github.com/mshahidbhatti)
