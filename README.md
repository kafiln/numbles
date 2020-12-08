## Run locally

To run this project in your local machine all you need is docker:

- Create a `.env` file based on values in `.env.example` and change those values according to your needs.

```
cp .env.example .env
```

- Run `docker-compose`

```
docker-compose up --build
```

- You should be then able to visit:
  - `http://localhost:3000` to access the front
  - `http://localhost:5000/api` to access the backend server
