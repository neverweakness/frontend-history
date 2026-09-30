# Сложно сосредоточиться

Учебный проект: адаптивная информационная страница о том, почему сложно концентрироваться и что снижает внимание (многозадачность, дофамин, еда, гаджеты и др.), с переключением тем оформления.

**Демо:** https://neverweakness.github.io/frontend-history/03-slozhno-sosredotochitsya/

## Возможности

- Три темы: светлая, тёмная и автоматическая (по `prefers-color-scheme`).
- Выбранная тема сохраняется в `localStorage`.
- Сетка на CSS Grid, адаптивная вёрстка под разные ширины экрана.
- Переменные CSS для цветов и размеров, отдельные файлы для светлой и тёмной темы.

## Стек

HTML5, CSS3 (custom properties, grid, media queries), чистый JavaScript.

## Запуск

Откройте `index.html` в браузере (после клонирования):

```bash
git clone https://github.com/neverweakness/frontend-history.git
cd frontend-history/03-slozhno-sosredotochitsya
```

## Структура

```
index.html           — разметка
scripts/script.js    — переключение и сохранение темы
styles/              — variables, globals, light, dark, style
fonts/               — IBM Plex Mono
images/              — иллюстрации, favicon
```

## Заметки

Проект сделан в декабре 2023 – феврале 2024: практика CSS-переменных, тем оформления и адаптивной вёрстки.

> Проект перенесён из отдельного репозитория [slozhno-sosredotochitsya](https://github.com/neverweakness/slozhno-sosredotochitsya) в архив ранних работ [frontend-history](https://github.com/neverweakness/frontend-history) с сохранением истории коммитов.
