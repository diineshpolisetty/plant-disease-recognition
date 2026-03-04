# Plant Disease Detection — Repository Overview

This repository contains a Flask web application and model artifacts for plant disease detection using CNNs and PyTorch.

Repository layout:
- `Plant-Disease-Detection-main/` — primary project folder (contains the original project files and notebooks).
- `Flask Deployed App/` — Flask application and web UI.
- `Model/` — notebooks and model artifacts.
- `demo_images/`, `test_images/` — example images and fixtures.

Quick start
1. Change into the Flask app folder:

```bash
cd "Plant-Disease-Detection-main/Flask Deployed App"
```

2. Create and activate a virtual environment (Python 3.8+ recommended):

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Place the pretrained model (`plant_disease_model_1.pt`) into the `Flask Deployed App` folder (link available in project README), then run:

```bash
python app.py
```

What I changed
- Added `LICENSE` (MIT).
- Added repository-level `README.md` with quick start instructions.
- Added a GitHub Actions workflow to run formatting and linting on pushes and PRs.
- Added a `.gitignore` (already committed) to exclude virtual environments, model files, and uploads.

What I can do next (automated)
- Run `black` across Python files and commit formatting changes.
- Add more CI steps (tests, packaging) or create releases.

If you want me to continue automatically applying these next steps, tell me and I'll run them now.
