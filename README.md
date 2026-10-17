# BZ_dev — Богдан Жадан, Python Backend Developer

Персональная визитка: backend на Python, базы данных, ML-сервисы и DevOps.
Опыт, проекты, стек и контакты.

**Сайт:** https://bogdanzhf.github.io/BZ_dev/

**Связь:** [Telegram @Bogdanzhd](https://t.me/Bogdanzhd)

## Структура

```
index.html   разметка и тексты
base.css     дизайн: хром, отражения, анимации, адаптив
theme.css    тема BZ_dev: электрический синий, фоновая сетка
script.js    терминал, 3D-наклон, счётчики, появление при скролле
```

Чистые HTML / CSS / JavaScript без сборки. Адаптив: телефоны от 320px, планшеты, десктоп.

После правок CSS/JS увеличьте `?v=N` в ссылках на файлы в `index.html` — так посетители сразу получат свежую версию.

## Локальный запуск

```bash
python -m http.server 5173
```

## Публикация

Каждый пуш в `main` публикует сайт на GitHub Pages через `.github/workflows/pages.yml`.
