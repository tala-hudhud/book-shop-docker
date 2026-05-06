# Book Shop Dockerization

This project runs the Book Shop Django app using Docker Compose.

It uses three containers:

- `db` for PostgreSQL
- `backend` for the Django app
- `nginx` as a reverse proxy on port 80

## Files

- `Dockerfile` builds the Django backend image
- `docker-compose.yml` runs the three services together
- `.env.example` shows the needed environment variables
- `nginx/nginx.conf` contains the Nginx reverse proxy config
- `requirements.txt` contains the Python packages

## Setup

Clone the repository:

```bash
git clone https://github.com/tala-hudhud/book-shop-docker.git
cd book_shop/book-shop