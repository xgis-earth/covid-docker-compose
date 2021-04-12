# Containerised covid globe app using docker-compose

## Installation

Check out scripts from Git:

```bash
git clone https://github.com/xgis-earth/covid-docker-compose.git covid && cd covid
```

Edit configuration files:

```bash
cp .env-dist .env # edit any relevant variables you need changed.
```

Build and start containers:

```bash
docker-compose up --build -d
```

