# Закрывающий тег

Учебный проект: адаптивный лендинг вымышленного медиа о фронтенде «Закрывающий тег» с ретро-стилем (шрифт Press Start 2P), анимациями и переключением тем.

**Демо:** https://neverweakness.github.io/frontend-history/04-zakryvayushchiy-teg/

## Возможности

- Три темы оформления: светлая, тёмная, авто; выбор сохраняется в `localStorage`.
- Анимированная кнопка «лайк» с сердечком (SVG + CSS-анимации).
- Адаптивная вёрстка (медиазапросы), изображения в PNG и WebP.
- Оптимизированные SVG-иконки, переменные CSS, локальные шрифты.

## Стек

HTML5, CSS3 (custom properties, animations, grid), чистый JavaScript.

## Запуск

Откройте `index.html` в браузере (после клонирования):

```bash
git clone https://github.com/neverweakness/frontend-history.git
cd frontend-history/04-zakryvayushchiy-teg
```

## Структура

```
index.html            — разметка страницы
scripts/              — like.js (лайки), set-theme.js (темы)
styles/               — globals, variables, themes, animations, style
fonts/                — Inter, Press Start 2P
images/, svg/         — графика (в т.ч. оптимизированные версии)
```

## Заметки

Проект сделан в феврале–марте 2024: самая большая по объёму вёрстка из учебных работ, практика тем, анимаций и оптимизации графики.

> Проект входит в архив ранних работ [frontend-history](https://github.com/neverweakness/frontend-history); история коммитов сохранена.