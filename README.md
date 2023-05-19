# Dockerizing DRF Cinema

API service for cinema management written on DRF

```
git clone https://github.com/Litvinenko23/movie_cinema_api.git
python -m venv venv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
pip install -r requirements.txt
export DB_HOST=DB_HOST
export DB_NAME=DB_NAME
export DB_USER=DB_USER
export DB_PASSWORD=DB_PASSWORD
export SECRET_KEY=SECRET_KEY
python manage.py migrate
python manage.py runserver
```

## Run with docker

```
docker-compose build
docker-compose up
```

### Getting access

- create user /api/user/register/
- get access token /api/user/token/


### Features
- JWT authenticated
- Admin panel /admin/
- Documentation is located at /api/doc/swagger/
- Managing orders and tickets
- Creating movies with genres, actors
- Creating cinema halls
- Adding movie sessions
- Filtering movies and movie sessions

### Endpoints
![image](https://github.com/Litvinenko23/movie_cinema_api/assets/64659599/83146522-1b65-4837-9aa5-02fef0618b3e)
![image](https://github.com/Litvinenko23/movie_cinema_api/assets/64659599/d42fbf53-e45f-4d91-9c61-15845625bc0f)
