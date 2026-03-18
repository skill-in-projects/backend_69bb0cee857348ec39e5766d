# CareLink - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69bb0cee857348ec39e5766d_user:BAv%2AVOh%23eOT8%5E9SG3KE7Ep%2ANb1IV%5Eon%26@ep-royal-base-ajh30k5q.c-3.us-east-2.aws.neon.tech:5432/AppDB_69bb0cee857348ec39e5766d?sslmode=require`

## Web API

**WebApi URL:** https://webapi69bb0cee857348ec39e5766d-production.up.railway.app

**Swagger API Tester URL:** https://webapi69bb0cee857348ec39e5766d-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
