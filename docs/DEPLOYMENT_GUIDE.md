# Website - Deployment Guide

## Tech Stack
| Technology | Purpose |
|-----------|---------|
| PHP | Backend logic |
| MySQL | Database |
| HTML/CSS | Frontend |
| JavaScript | Interactivity |

## Local Setup
```bash
git clone https://github.com/coda-coda-23/website.git
cd website
# Place in web server document root (Apache/Nginx)
# Import database schema
# Configure .env with DB credentials
```

## Deployment Options
| Platform | Requirements |
|----------|-------------|
| Shared Hosting | PHP 7.4+, MySQL 5.7+ |
| VPS | LAMP/LEMP stack |
| Docker | docker-compose up |