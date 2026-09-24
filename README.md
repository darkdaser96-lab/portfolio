# Портфолио Артёма

Статический одностраничный сайт-портфолио: боты и небольшие сервисы.

Контакт: [t.me/darkdaser](https://t.me/darkdaser)

## Стек

- HTML + CSS + небольшой JS (scroll reveal)
- Без бэкенда, форм, ключей и аналитики

## Локальный просмотр

Откройте `index.html` в браузере или поднимите простой сервер:

```bash
python3 -m http.server 4173
```

## Деплой на Vercel

1. Залейте репозиторий на GitHub.
2. В [Vercel](https://vercel.com) создайте проект и подключите этот репозиторий.
3. Framework Preset: **Other** (статический сайт).
4. Build Command оставьте пустым, Output Directory — корень репозитория.
5. Deploy — получите production URL.

Или через CLI:

```bash
npx vercel --prod
```

## Структура

```
index.html   — страница
styles.css   — стили
script.js    — лёгкий scroll reveal
```
