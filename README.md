# mWAR Calculator

A customizable WAR (Wins Above Replacement) calculator for MLB players. Adjust stat weights to create your own formulas and compare to FanGraphs WAR and Baseball Reference WAR.

## Features

- 📊 Customizable stat weights for both batters and pitchers
- 🎯 Save and share custom formulas
- 📈 Dynamic leaderboards with your custom calculations
- 🔍 Player search and comparison tools
- ⚡ Real-time calculations with hybrid client/server architecture

## Tech Stack

**Frontend:**
- React + TypeScript
- Vite
- TailwindCSS + Shadcn/ui
- React Query
- Recharts

**Backend:**
- Fastify + TypeScript
- Drizzle ORM
- Pino logger
- Vitest + Supertest

**Database & Auth:**
- Supabase (PostgreSQL + Auth)

**Data Pipeline:**
- Python + PyBaseball
- Scheduled ETL jobs

**Hosting:**
- Vercel (Frontend)
- Railway (Backend + ETL)
- Supabase (Database + Auth)

## Project Structure

```
mwar-calculator/
├── shared/          # Shared calculation library
├── backend/         # Fastify API
├── frontend/        # React application
├── python-etl/      # Data fetching pipeline
└── database/        # SQL schemas and migrations
```

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- Python 3.9+
- PostgreSQL (or Supabase account)

### Installation

Coming soon...

## Documentation

See design documentation for comprehensive specifications.

## License

MIT

## Contributors

Made with ❤️ for baseball fans
