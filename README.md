# psy profile report

статический html-отчет с инфографикой по тестам 2022 vs 2024.

## локальный запуск

```bash
npm start
```

по умолчанию сервер слушает `PORT` или `3000`.

## что внутри

- `public/index.html` — сам отчет
- `server.js` — минимальный node-сервер для static deploy
- `package.json` — стартовая команда

## быстрый деплой

подходит для railway, render, fly.io и любых платформ, которым нужен `start` command.

если хочешь залить на github pages, сервер не нужен: можно просто публиковать `public/index.html` как статический файл.
