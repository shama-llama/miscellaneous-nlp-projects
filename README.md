# Miscellaneous NLP Projects

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white)](https://docs.python.org/3.12/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository is a collection of assignments that were done as part of the Natural Language Processing (CoSc 6252) course. The notebooks cover topics in morphological analysis.

## Projects

### 1. Morphological Analysis

- **Notebook:** `notebooks/morphological_analysis.ipynb`
- **Description:** Morphological word generation for ግድል.

### 2. Finite State Automata

- **Notebook:** `notebooks/finite_state_automata.ipynb`
- **Description:** Conversion from nondeterministic finite automata (NFA) to deterministic finite automata (DFA) for Amharic pronouns using `automata-lib`.

## Required Packages

The following system-level dependencies need to be installed before running the projects:

```bash
sudo dnf install graphviz-devel
sudo dnf install cairo-devel
sudo dnf install pango-devel
```

## Project Setup

This project uses `uv` for package management. `uv` is an extremely fast Python package and project manager, written in Rust that can be used as a drop-in replacement for `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`.

- **`uv` Installation**

    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

- **Clone the Repository:**

    ```bash
    git clone https://github.com/shama-llama/miscellaneous-nlp-projects.git
    cd miscellaneous-nlp-projects
    ```

- **Create a Virtual Environment and Install Dependencies with `uv`:**

    ```bash
    uv venv
    uv pip install -e .
    ```

- **Activate the Virtual Environment:**

    ```bash
    source .venv/bin/activate
    ```

- **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

    Navigate to the `notebooks/` directory to run the analysis.

## License

This project is licensed under the terms of the [MIT](LICENSE) open source license.
