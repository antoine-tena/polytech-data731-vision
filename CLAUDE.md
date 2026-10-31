# Vision

Handwritten NumPy AI recognising handwritten or printed digits.

## Repo map

- `backend/pipeline/`: `sources.py` (MNIST in `data/raw/`, outside repo), `printed.py` (digits from machine fonts), `dataset.py`, `transforms.py` (to MNIST format), `recognition.py`, `reasoning.py` (neuron votes, decisive pixels), `neuron_shapes.py`, `activity.py`, `figures/` (one module per screen).
- `backend/network/`: NumPy network. `model.py` (784 → ReLU → 10), `layers.py`, `activations.py`, `losses.py`, `optimizers.py`, `training.py`, `train.py` (`uv run python -m network.train`), `evaluate.py`, `sample.py`.
- `backend/notebooks/`: marimo; `backend/data/`: `sample/` and `models/` committed; `backend/tests/`.
- `frontend/app.py`: entry (Présentation, Lexique: `home.py`, `glossary.py`); `frontend/dashboard/`: `slides.py` (order, ◀ ▶, keyboard), `sections.py`; parts `project.py`, `learning.py`, `training.py`, `choice.py` (`canvas.py`, `examples.py`, `images.py`), `reasoning.py`, `live.py`; `formula.py`, `explanations.py`, `loaders.py`, `constants.py`; `frontend/tests/`.
- `docs/backlog/`; `charter.toml`; `.claude/rules/kiln/`.
