[README.md](https://github.com/user-attachments/files/27966176/README.md)
# x1w4q — personal links page

![preview](preview.png)

Минималистичная страница-визитка с анимациями, кастомным аудиоплеером и интерактивными эффектами.

## ✨ Фичи

- **Анимированный фон** — canvas частицы с линиями связей
- **Аудиоплеер** — встроенный трек «зарница», волновой прогресс-бар на canvas
- **Ripple эффект** — Material-style ripple при клике на кнопки
- **Плеер скрывается/открывается** — кнопка закрытия (↓) + боковая кнопка открытия (♫)
- **Счётчик посещений** — localStorage (локальный, без бэкенда)
- **Splash экран** — анимированный морфинг-лоадер
- **Кастомный курсор** — голубой кружок на десктопе
- **Вибрация** — тактильный отклик на Android при нажатии кнопок
- **OG-теги** — мета-данные для Telegram/соцсетей
- **Один файл** — весь сайт в одном `index.html` (включая аудио в base64)

## 🚀 Как запустить

Просто открой `index.html` в браузере. Всё. Без сборки, без зависимостей, без серверов.

```bash
# или через любой локальный сервер
npx serve .
# или
python3 -m http.server 8000
```

## 📂 Структура

```
index.html   — весь сайт (HTML + CSS + JS + аудио base64)
preview.png  — скриншот для README
README.md    — это файл
```

## 🌐 Деплой на GitHub Pages

1. Создай репозиторий на GitHub
2. Загрузи файлы (`index.html`, `preview.png`)
3. Settings → Pages → Source: `main` branch, `/ (root)`
4. Сайт будет на `https://твой-ник.github.io/название-репо/`

## 🛠 Технологии

- Pure HTML/CSS/JS — zero dependencies
- Canvas API — фон + прогресс-бар
- Web Vibration API — тактильный отклик (Android)
- CSS animations + transitions

## 📝 Лицензия

MIT

---

*made by x1w4q*
