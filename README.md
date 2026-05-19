# x1w4q — Personal Link Page

Персональная страница-визитка с Material Design 3.

![preview](preview.png)

## Возможности

- **Три вкладки** — Главная (профиль + счётчик просмотров), Соцсети (TikTok, Telegram, канал), Настройки
- **Музыкальный плеер** — встроенный трек «Зарница» с плавным fade-in, прогресс-бар, кнопка play/pause
- **Настройки**
  - Тёмная / светлая тема (MD3 switch)
  - 5 акцентных цветов (оранжевый, фиолетовый, зелёный, розовый, синий)
  - Громкость — кастомный MD3 слайдер с touch-поддержкой
  - Язык — RU / EN
- **Анимированные частицы** — фоновые блёстки на canvas
- **Splash screen** — морф-анимация при загрузке
- **Easter egg** — набери `x1w4q` на клавиатуре
- **Material Design 3** — карточки, навбар, переключатели, слайдер, elevation, ripple
- **Полностью автономный** — один HTML файл (~2.4 MB с base64 аудио), никаких зависимостей

## Запуск

Просто откройте `index.html` в браузере. Никакой сборки или сервера не нужно.

```
open index.html
# или
python3 -m http.server 8080
```

## GitHub Pages

1. Создайте репозиторий на GitHub
2. Загрузите `index.html` и `README.md`
3. Settings → Pages → Source: `main` branch → Save
4. Сайт будет доступен по адресу `https://<username>.github.io/<repo>/`

## Счётчик просмотров

В GitHub-версии счётчик работает через `localStorage` (локально на устройстве).  
В серверной версии — через API + базу данных.

## Стек

- Чистый HTML / CSS / JavaScript
- Material Design 3 (кастомная реализация)
- Canvas API (частицы)
- Web Audio (встроенный base64 трек)

## Структура

```
index.html    — весь сайт в одном файле
README.md     — этот файл
preview.png   — превью для README
```

## Автор

**x1w4q** — content maker / streamer

---

v2.0 · 2026
