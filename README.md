# django-guide

Учебник и справочник по Django на русском.

- **Сайт:** https://kilmanr.github.io/django-guide/
- **Источник материала:** docs.djangoproject.com (адаптировано и переведено)
- **Разделы:** шпаргалка команд, tutorial (части 1–7), справочник
  (models/ORM, views/urls/templates/forms, admin/settings/deploy), Docker для Django.

## Как собран сайт

Исходный контент — Markdown (`out/**/*.md`), собирается в HTML скриптом
`scripts/md2html.py` с локальным шрифтом Noto Sans (woff2) и адаптивным CSS.
Публикуется на GitHub Pages из ветки `gh-pages`.

## Локально

Открой `index.html` в браузере — сайт полностью работает без интернета.