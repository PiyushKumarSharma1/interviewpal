# InterviewPal — Personalized DSA Analytics Tracker
Full-stack analytics app tracking 100+ algorithm categories with streaks, progress graphs, and weakness detection.

**Stack:** FastAPI + JWT + PostgreSQL + SQLAlchemy + Alembic · React dashboard · Docker
**Repo status:** Backend auth + DB scaffold live here. Full local build (Express + sqlite + ML prototype + evals) lives in `Documents/New project` — consolidating to this repo next.

## Run backend
```
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```
- `GET /health` → ok
- `GET /db-check` → db ok
- Auth: `app/api/auth.py` (JWT)

## Roadmap
- [ ] Port React dashboard + 100+ category analytics from local build
- [ ] Merge AI Resume Screener (TF-IDF + spaCy + scikit-learn Flask API) as `/match` service
- [ ] Docker Compose (api + db + ui) + CI + demo screenshots
- [ ] Live demo + Swagger link

Author: Piyush Kumar Sharma — MSU Data Science '27 — Piyush.adm12@gmail.com
