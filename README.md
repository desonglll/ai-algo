# AI Algos

## Setup Instructions

This project uses Conda for virtual environments and Poetry for dependency management. Follow these steps to set it up.

### Prerequisites

Ensure you have the following installed:

- [Anaconda or Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [Poetry](https://python-poetry.org/docs/#installation)

### Steps

**Clone the repository:**

```bash
git clone https://github.com/desonglll/ai-algo
cd ai-algo
```

**Create and activate a Conda environment:**

```bash
conda create --prefix ./venv python=3.12 
conda activate venv
```

**Install Poetry:**

```bash
pip install poetry
```

**Install project dependencies:**

```bash
poetry install
```

## Add Code

```latex
\subsection{示例代码}
\begin{lstlisting}

\end{lstlisting}
```

## Clone

```shell
git clone --recursive <repository_url>
```

After normal clone, we need to clone sub repository.

```shell
git submodule update --init --recursive
```