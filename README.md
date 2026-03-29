# TextAnalytics API

> NLP service for sentiment analysis, entity extraction, and summarization

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
FastAPI, PostgreSQL, Docker, Redis

## 🏗️ Architecture
Backend service with FastAPI, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/textanalytics-api
cd textanalytics-api

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
