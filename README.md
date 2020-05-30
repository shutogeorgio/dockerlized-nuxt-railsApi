## Dockerlized Fullstack Template
### Stack
- Frontend: Nuxt.js
- Backend: Rails
- DB: Postgresql

### Get Started
#### General
bash 
```
$ docker-compose build
```

#### Frontend
```
$ docker-compose run --rm frontend npx create-nuxt-app
$ docker-compose up front
```

localhost:8080

#### Backend
```
$ docker-compose run --rm backend rails new . -f -d postgresql --api
$ docker-compose build back
$ docker-compose run --rm backend rails db:create
```
