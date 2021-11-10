# Docker PHP 5.3

This repository is for working with code in older PHP 5.3 environments.

## What's included:
- PHP 5.3
- MySQL 5.7
- phpMyAdmin
- Code Server (VS Code)

## Default Ports
- **PHP** (http://localhost:5316)
- **phpMyAdmin** (http://localhost:5320) => Use username and password set in `.env` for MySQL to login
- **Code Server** (http://localhost:5319) => Use password set in `.env`


## Installation
1. Create a project directory locally.
2. Download repo into project directory.
3. Open terminal and navigate to project directory.
4. Copy contents of `.sample-env` to `.env` (Use `cp .sample-env .env`).
5. Update contents of `.env` with project specific information
6. Within the `web` directory place all the project code that is needed for your project.
7. From the project root execute: `docker-compose up -d`
8. Visit


## Notes
- To stop the Docker containers execute from the project root: `docker-compose stop`


