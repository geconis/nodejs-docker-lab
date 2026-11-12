
## Технології
- Node.js
- Docker
- GitHub Actions
- Docker Hub
- Render

## Файли проєкту
- index.js — код застосунку
- package.json — налаштування проєкту
- Dockerfile — інструкції для Docker
- .dockerignore — виключення зайвих файлів

## Запуск

Збірка образу:
```bash
docker build -t nodeapp:test .
```

Запуск контейнера:
```bash
docker run -d --name nodeapp -p 3000:3000 nodeapp:test
```

## Docker Hub
gekaris/nodeapp

## Розгортання
https://nodeapp-main.onrender.com