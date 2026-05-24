# Гайды от «Давай попроще, Руслан»

Статический сайт для публикации HTML-гайдов на GitHub Pages.

## Как открыть локально

Откройте файл `index.html` в браузере. Сайт сделан без сборщика, поэтому отдельная установка зависимостей не нужна.

## Как залить на GitHub

```bash
git add .
git commit -m "Add guides site"
git push -u origin main
```

## Как включить GitHub Pages

1. Откройте репозиторий на GitHub.
2. Перейдите в `Settings` → `Pages`.
3. В блоке `Build and deployment` выберите `Deploy from a branch`.
4. Укажите ветку `main` и папку `/root`.
5. Сохраните настройки и дождитесь публикации.

## Где добавлять новые гайды

Новые страницы добавляйте в папку `guides/`, например `guides/new-guide.html`.

Карточки новых гайдов добавляются на главной странице в блоке `#guides`.

Общие стили лежат в `assets/css/styles.css`, JavaScript — в `assets/js/main.js`, иллюстрации — в `assets/img/`.
