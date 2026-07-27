# saas-hermes-agent

The agent that grows with you

## Source
Original: https://github.com/NousResearch/hermes-agent

## SaaS Wrapper
- FastAPI backend: saas/main.py
- Landing page: site/index.html

## Deploy
```bash
cd saas && pip install -r requirements.txt && uvicorn main:app --host 0.0.0.0 --port 8080
```

## Status
Prototype scaffolded by CEO Agent on 2026-07-27.
