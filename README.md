# MHQA Plantio System

## Project Overview
This is a fullstack application with:
- **Frontend**: ReactJS application served by Nginx
- **Backend**: Java Spring Boot 2.1
- **Database**: PostgreSQL

## Repository Structure
- Frontend: <mcurl name="Plantio-frontend" url="https://github.com/marcelquin/Plantio-frontend"></mcurl>
- Backend: <mcurl name="plantio-backend" url="https://github.com/marcelquin/plantio-backend"></mcurl>

## Infrastructure
- **Frontend Deployment**: Containerized React app served via Nginx
- **Backend Deployment**: Spring Boot application
- **Database**: PostgreSQL with backup in `Database Backup/dados.tar`
- **Kubernetes**: Deployment configurations in `k3s/` directory

## Getting Started
1. Clone both repositories
2. Follow setup instructions in each repository's README
3. Deploy using Kubernetes configurations provided

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.