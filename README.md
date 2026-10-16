x1w4q — Link in Bio
Минималистичный одностраничный сайт-визитка в стиле Material Design 3 Expressive с анимированным прелоадером, морфингом фигур и тёмной/светлой темой.
🔗 Демо
Открой index.html в браузере — никакой сборки не нужно.
✨ Что внутри
Loading Indicator
Точный порт официального MD3 Expressive Loading Indicator из material-components-android и @alerix/m3-loading-indicator (Apache 2.0).
• 7 фигур: Soft Burst → Cookie 9 → Pentagon → Pill → Sunny → Cookie 4 → Oval
• SVG-пути взяты напрямую из официальных Material Design asset-файлов
• Spring physics: stiffness=200, dampingRatio=0.6 (12 sub-steps, semi-implicit Euler)
• Формула ротации из LoadingIndicatorAnimatorDelegate.java: (50+90)×cycle + 50×tf + 90×sf
• Contained вариант: круглый контейнер secondary-container, фигура on-secondary-container
• Canvas HiDPI с devicePixelRatio
Дизайн (MD3 Expressive 2025)
• Полная палитра MD3: все цветовые роли для тёмной и светлой тем
• Shape tokens: xs=4dp · sm=8dp · md=12dp · lg=16dp · xl=28dp · full=9999px
• Elevation через тональные оверлеи (не тени)
• State layers: hover .08, pressed .12 — по спеке MD3
• Google Sans + Google Sans Display + Material Symbols Rounded
Эффекты
• Плавающие MD3-фигуры на фоне (blob, pill, diamond, squircle)
• Shimmer-градиент на имени (primary ↔ on-surface)
• Spring-bounce аватара при наведении + glow
• 3D tilt карточек при движении мыши (perspective rotateX/Y)
• Цветная border-рамка карточки при hover
• Icon spring-bounce + поворот при hover
• Staggered fade-in + slide-up при появлении
• Ripple (MD3 bounded) при клике
Прочее
• Тёмная/светлая тема с сохранением в localStorage
• Полная адаптивность: мобильный + десктоп
• Safe area insets (iPhone notch)
• aria-label, семантические теги, focus-visible
• prefers-reduced-motion поддержка
• Один HTML-файл, ноль зависимостей (только Google Fonts через CDN)
📁 Структура
index.html   ← весь сайт: HTML + CSS + JS в одном файле
README.md
🚀 Деплой
GitHub Pages
1. Залей репозиторий на GitHub
2. Settings → Pages → Source: main / root
3. Сайт будет доступен по адресу https://<username>.github.io/<repo>/
Vercel / Netlify
Просто перетащи папку — статика без конфига.
🔧 Кастомизация
Всё в одном файле — открой index.html в любом редакторе.
Что менять
Где искать
Ссылки и ники
<nav class="links-list">
Имя и статус
<h1 class="profile-name"> и <p class="profile-status">
Аватар
<div class="avatar"> — замени <img> или верни букву
Цвета темы
CSS-переменные --c-primary, --c-secondary и т.д.
Размер лоадера
var CSS_SIZE в JS
Скорость морфинга
var DURATION_MS (по умолчанию 650)
📜 Лицензия
MIT — делай что хочешь.
SVG-пути фигур и алгоритм аниматора портированы из material-components-android и m3-loading-indicator под лицензией Apache 2.0 (Copyright Google LLC / Aler1x).
