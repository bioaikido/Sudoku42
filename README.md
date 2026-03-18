# Logos Games PWA

## Структура
```
LogosGames_PWA/
├── sudoku42.html          — Судоку42 (9×9)
├── hawaiian.html          — Гавайское Судоку (4×4)
├── manifest_sudoku42.json — PWA манифест для Судоку42
├── manifest_hawaiian.json — PWA манифест для Гавайского Судоку
├── sw_sudoku42.js         — Service Worker для Судоку42
├── sw_hawaiian.js         — Service Worker для Гавайского Судоку
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    ├── apple-touch-icon.png  (180×180, для iOS)
    └── favicon-32x32.png

## Установка на сервере
Разместите все файлы в одной папке на HTTPS-сервере.
Каждая игра открывается отдельно и устанавливается как отдельное PWA.

## Установка на телефон
1. Откройте sudoku42.html или hawaiian.html в браузере
2. Нажмите «Добавить на главный экран»
3. Игра работает офлайн после первого открытия
