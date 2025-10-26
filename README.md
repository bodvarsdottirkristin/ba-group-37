# Business Analytics Project

A lightweight starter repo for a data/analytics workflow.

## Python version
This project targets **Python 3.12.6**. Make sure you have that version available (via `pyenv`, official installers, or your system package manager).

## Quick start

```bash
# 1) Create and activate a virtual environment
python3.12 -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows (PowerShell)
# .venv\Scripts\Activate.ps1

# 2) Upgrade pip + install deps
python -m pip install --upgrade pip
pip install -r requirements.txt

# 3) (Optional) Register the venv in Jupyter
python -m ipykernel install --user --name business-analytics --display-name "Python 3.12.6 (business-analytics)"
```

## Repo layout

```
.
├─ .gitignore
├─ .python-version             # for pyenv users (optional helper)
├─ requirements.txt
├─ README.md
├─ src/
│  └─ __init__.py
├─ notebooks/
│  └─ 00_starter.ipynb
└─ data/                       # put data files here (ignored by git)
```

## Notes

- Keep data files in `data/` (git-ignored by default).
- Add extra packages to `requirements.txt` as needed and re-run `pip install -r requirements.txt`.
- For tidy code, consider enabling `pre-commit` later.
