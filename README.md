# HandyScan – Handwriting to Text

**Goal**: Upload an image of handwritten notes and return typed, copyable text.

## Structure
- `backend/`: FastAPI server and OCR logic
- `app/`: Flutter mobile app
- `docs/`: product notes, API sketch, decisions

## Quickstart (backend)
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn backend.main:app --reload
```

