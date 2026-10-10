# AI-Driven Solar Air Dryer

A notebook-based smart-dryer demo that trains a multi-output neural network to
predict fan speed, heater state, and safety warnings from temperature, humidity,
elapsed time, and moisture.

## Project files

- `Miniproject(F) (1).ipynb` — data preparation, model training, evaluation, and
  sample prediction.
- `smart_dryer_dataset.csv` — 1,000 synthetic example rows for the notebook.

The included dataset is synthetic and is intended for demonstration, not for
operating or controlling real equipment.

## Run

Create and activate a virtual environment, install the dependencies, then launch
Jupyter from this folder:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m pip install notebook
jupyter notebook "Miniproject(F) (1).ipynb"
```

Run the notebook cells from top to bottom. It expects the CSV file to remain in
the same folder.
