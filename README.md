# Family Health AI Coordinator (MVP)

An AI-powered personal and family health assistant designed to aggregate medical records, track pediatric WHO growth percentiles, and provide personalized daily lifestyle recommendations based on local weather and Air Quality Index (AQI).

## Planned Architecture (Claude Code Build Day)
- **Frontend:** React / Next.js + Tailwind CSS (Multi-profile family dashboard)
- **Backend & AI:** Python (FastAPI) + Claude API (Structured JSON extraction from lab PDFs)
- **Database:** PostgreSQL (Supabase) with relational schema for family profiles, WHO growth standards, vaccinations, and medication schedules
- **External APIs:** OpenWeatherMap & AQICN for environmental context triggers
