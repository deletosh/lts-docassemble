## Docassemble development setup
A simple docassemble set up on your local development machine for trial and development processes.

The app runs on [http://localhost/](http://localhost/) and the postgres database console on   [http://localhost:8080](http://localhost:8080)

### Getting Started
1. Clone this repo `git clone git@github.com:thedeletosh/lts-docassemble.git`
2. If you've never installed docker, install [docker](https://docs.docker.com/get-docker/)
3. Run using `docker compose up -d`  
4. After around 10 mins of initial setup, your app will be available on [http://localhost/](http://localhost/) (default username is `admin@admin.com` and password is `password`)
5. To shut it off, run, `docker compose up -d`
