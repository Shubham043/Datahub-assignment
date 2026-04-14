# DataHub — Analytics Platform

A customized and Dockerized deployment of Apache Superset, rebranded as **DataHub** — a unified analytics and data visualization platform.

## Customizations Made

- **Branding** — Replaced Apache Superset logo with DataHub logo across navbar and login page
- **Purple Theme** — Changed primary color from blue to purple (`#7C3AED`) across buttons, links, and UI elements
- **Login Page** — Custom title "Sign in to DataHub" with updated subtitle
- **Welcome Banner** — Added a branded purple welcome banner on the home dashboard
- **Favicon** — Custom DataHub favicon in browser tab
- **App Name** — Updated from "Superset" to "DataHub" throughout the app

## Tech Stack

- Apache Superset (frontend: React, backend: Python/Flask)
- PostgreSQL
- Redis
- Docker & Docker Compose

## How to Run

### Prerequisites
- Docker Desktop installed and running

### Steps

```bash
# 1. Clone the repo
git clone https://github.com/Shubham043/datahub-superset.git
cd datahub-superset

# 2. Build the custom Docker image
docker build -t datahub-superset .

# 3. Start all services
docker-compose -f docker-compose-datahub.yml up -d
```

### Access the app
Open your browser and go to: `http://localhost:8088`

**Default credentials:**
- Username: `admin`
- Password: `admin`

## Screenshots

> Login page and dashboard screenshots can be added here.

## Author

Shubham Sharma