# Book Shop - Django App with Docker

## Requirements
- Docker
- Docker Compose

## Setup & Run

1. Clone the repository:
git clone https://github.com/FathiAl-hammouri/book_shop.git
cd book_shop

2. Copy the environment file:
cp .env.example .env

3. Edit the .env file with your values

4. Run the app:
docker compose up --build

5. Run migrations:
docker compose exec backend python manage.py migrate

## Services
- **db**: PostgreSQL database on port 5432
- **backend**: Django app on port 8000
- **nginx**: Reverse proxy on port 80

## Access the app
Open your browser and go to: http://localhost