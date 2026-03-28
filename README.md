# psy profile report

статический html-отчет с инфографикой по тестам 2022 vs 2024.

## что внутри

- `public/index.html` — сам отчет
- `Staticfile` — конфиг для static deploy на railway

## деплой

репозиторий специально сделан как pure static site.
railway должен брать `Staticfile` и отдавать содержимое папки `public`.
