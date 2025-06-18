# SmartTrip – Scalable Travel Planning Web App

**Tech Stack**: React.js, Node.js, Express.js, MongoDB, AWS Lambda, S3

## About
SmartTrip is a full‑stack travel planner that lets users search, save and share personalised itineraries.

## Key Features
- RESTful APIs (Node.js + Express) for trips, places and user profiles
- Google Maps & Places API integration for routing and POI details
- Front‑end built with React (mobile‑first, responsive)
- Serverless media storage on Amazon S3 and business logic on AWS Lambda
- JWT‑based authentication & role‑based access control
- Docker‑compose for local development

## Local Setup
```bash
git clone <repo-url>
cd SmartTrip
docker compose up --build
```

## Deployment
- Create an S3 bucket for public assets
- Deploy Lambda functions via AWS SAM / Serverless
- Point frontend to the deployed API Gateway endpoints

---
