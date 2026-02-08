# Artem Portfolio Site

Одностраничный сайт-портфолио для позиции `Senior Sexter / Sales Manager`.

## Что внутри

- `index.html` - структура страницы и контент
- `style.css` - визуальный стиль, адаптив, анимации
- `script.js` - reveal-анимации и lightbox для скриншотов
- `images/` - изображения (в проект уже добавлены `proof-1.jpg ... proof-5.jpg`)

## Запуск локально

```powershell
cd "c:\Users\Ynifar\Desktop\adult-job-board\portfolio-site"
python -m http.server 5500
```

Открой в браузере: `http://localhost:5500`

## Что заменить перед отправкой работодателю

1. При необходимости замени `images/proof-1.jpg ... images/proof-5.jpg` на новые скрины статистики.
2. Контакты в блоке `#contact` (email/telegram), если нужны другие.
3. KPI в таблице и в карточках, если добавятся новые результаты.
