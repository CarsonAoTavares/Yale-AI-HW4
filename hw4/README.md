# Campus Customs

Yale merchandise storefront with a FastAPI catalog and shopping assistant.

## Local data

Keep the supplied data pack outside Git and place it at `hw4/data/campus_customs.db` and `hw4/data/products/`.

## Start the backend

Create a Python virtual environment and install `requirements.txt`. From `hw4/backend/`, run `uvicorn main:app --reload --port 8000`.

## Start the frontend

From `hw4/frontend/`, run `npm ci` then `npm run dev`; open the Vite URL, normally `http://localhost:5173`. Vite proxies `/api` to FastAPI.

Copy `.env.example` to `.env` and set `PORTKEY_API_KEY` or `OPENAI_API_KEY`. Never commit `.env`.
