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
flutter run -d web-server
```

- browser
localhost:8888
