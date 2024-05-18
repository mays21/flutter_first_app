# Introduction

- Flutterの最初のアプリ
- Docker上で動かす

# Usage

‐ create
```
docker compose build
docker compose up -d
docker exec -it flutter bash

cd workspace
flutter create .
```

- execute
```
docker compose up -d
docker exec -it flutter bash

cd workspace
flutter create .
flutter run -d web-server --web-port=${WEB_SERVER_PORT} --web-hostname 0.0.0.0
```

- browser
localhost:8888
