# Посмотри в окно

Учебный проект: страница с поиском видео из «окон» разных городов. Данные подгружаются с учебного API, результаты отображаются карточками, выбранное видео воспроизводится на странице.

**Демо:** https://neverweakness.github.io/frontend-history/02-posmotri-v-okno/

## Возможности

- Форма поиска с фильтрами (город, время суток) и запросом к API.
- Карточки результатов на HTML-шаблонах (`<template>`), кнопка «Показать ещё».
- Прелоадер на время загрузки и понятное сообщение, если ничего не найдено.
- Асинхронная работа с сетью на `fetch` / `async-await`.

## Стек

HTML5, CSS3 (grid), чистый JavaScript. Без сборщиков и зависимостей.

## Запуск

Откройте `index.html` в браузере. Для загрузки данных нужен доступ в интернет, так как используется внешний учебный API.

```bash
git clone https://github.com/neverweakness/frontend-history.git
cd frontend-history/02-posmotri-v-okno
```

## Структура

```
index.html        — разметка и шаблоны
scripts/script.js — запросы к API, рендер карточек, состояние
styles/           — style.css, preloader.css, error.css
fonts/            — Oswald, Fira Sans Condensed
```

## Заметки

Проект сделан в ноябре 2023: практика DOM, шаблонов и асинхронных запросов.

> Проект входит в архив ранних работ [frontend-history](https://github.com/neverweakness/frontend-history); история коммитов сохранена.