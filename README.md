# World Cup Analytics Platform

A full-stack football analytics platform focused on the FIFA World Cup, providing live match data, player statistics, team insights, visualizations, and predictive analytics.

## Features

- Live match tracking
- Team and player statistics
- Match analytics dashboard
- Player comparison tools
- Interactive heatmaps and visualizations
- Historical World Cup data
- Predictive models and AI-powered insights (planned)

## Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS

### Backend
- FastAPI
- PostgreSQL
- SQLAlchemy

### Data & Analytics
- Football Data APIs
- Pandas
- NumPy
- Scikit-Learn

## Project Structure

```text
world-cup-platform/
├── frontend/
├── backend/
├── data/
├── notebooks/
└── docs/
```

## Setup

### Backend

```bash
conda activate worldcup
cd backend

uvicorn app.main:app --reload
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Roadmap

- [ ] Match pages
- [ ] Team pages
- [ ] Player profiles
- [ ] Live match statistics
- [ ] Heatmaps and event visualizations
- [ ] Player comparison dashboard
- [ ] Match prediction models
- [ ] AI-generated match summaries

## License

This project is for educational and portfolio purposes.
