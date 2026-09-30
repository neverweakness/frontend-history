# Frontend History

Архив моих ранних учебных проектов по вёрстке. Здесь собраны четыре лендинга, сделанные с октября 2023 по март 2024, — с сохранением полной истории коммитов. Репозиторий не развивается: это «история», по которой видно, как менялся уровень от простой вёрстки к темам, анимациям и адаптивности. Новые проекты живут в отдельных репозиториях.

**Галерея с живыми демо:** https://neverweakness.github.io/frontend-history/

## Хронология

| # | Проект | Период | Чему научился | Демо |
| --- | --- | --- | --- | --- |
| 01 | [Оно тебе надо](01-ono-tebe-nado) | окт 2023 | Семантическая вёрстка по макету, шрифты и SVG, автопроверка вёрстки в GitHub Actions | [открыть](https://neverweakness.github.io/frontend-history/01-ono-tebe-nado/) |
| 02 | [Посмотри в окно](02-posmotri-v-okno) | ноя 2023 | Первые запросы к API (`fetch`, `async/await`), HTML-шаблоны, прелоадер, обработка ошибок | [открыть](https://neverweakness.github.io/frontend-history/02-posmotri-v-okno/) |
| 03 | [Сложно сосредоточиться](03-slozhno-sosredotochitsya) | дек 2023 – фев 2024 | CSS-переменные, светлая/тёмная/авто темы, `localStorage`, CSS Grid, адаптивность | [открыть](https://neverweakness.github.io/frontend-history/03-slozhno-sosredotochitsya/) |
| 04 | [Закрывающий тег](04-zakryvayushchiy-teg) | фев – мар 2024 | Темы, CSS-анимации, анимированная кнопка «лайк», оптимизация графики (WebP, SVG) | [открыть](https://neverweakness.github.io/frontend-history/04-zakryvayushchiy-teg/) |

Подробное описание, возможности и структура каждого проекта — в `README.md` его папки.

## Что дальше

Новые проекты лежат в отдельных репозиториях, например [VK Music Downloader](https://github.com/neverweakness/vk-music-downloader) — расширение для браузера.

## Происхождение

Ранее каждый лендинг был отдельным репозиторием. Они собраны здесь через `git subtree` с полной историей коммитов.

## Запуск

Проекты статические, сборка не нужна:

```bash
git clone https://github.com/neverweakness/frontend-history.git
cd frontend-history/03-slozhno-sosredotochitsya
# откройте index.html в браузере
```
