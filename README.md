# SEM Tip Radius Backend

Python FastAPI backend for tip-radius measurement on SEM imagery.

Packages a research-style image analysis pipeline (`sem_analysis`) behind HTTP endpoints for health checks, protocol inspection, and analysis jobs.

## Stack

- **Backend:** Python 3.10+, FastAPI, Uvicorn
- **Scientific / ML tooling:** NumPy, SciPy, OpenCV, scikit-image, scikit-learn
- **Config:** YAML protocols, sample synthetic tip assets

## Features

- Analyze uploaded SEM tip images
- Configurable measurement protocol
- Sample data and pytest coverage for core geometry paths

## Quick start

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app:app --reload --port 8000
```

API docs: http://localhost:8000/docs

## Author

Pooja Sharma — [Pooja101117](https://github.com/Pooja101117)
