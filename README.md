# HelenLearnsNepali — Backend (Replit + GitHub)

## Run on Replit
```
pip install -r requirements.txt
uvicorn app.main:app --host 0.0.0.0 --port 8000
```

Open the web preview, test `/` and `/api/transliterate?q=तिमी`.

## Long-term practices
- Version control: push this repo to GitHub and create your Replit from that repo.
- Secrets: set env vars in **Replit → Secrets**, never commit `.env`.
- Health: `/health` endpoint for liveness checks.
- Deployment: Replit **Reserved VM** (always-on) when ready.
