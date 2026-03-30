# CollectMarket — Лендинг (Module A)

Рекламный лендинг для онлайн-сервиса объявлений коллекционных товаров.

## Запуск проекта

1. Скачай или клонируй папку проекта
2. Скопируй папку `media-files` из Google Drive рядом с HTML-файлами
3. Открой файл `index.html` в браузере

> Рекомендуется использовать расширение **Live Server** в VS Code для корректного отображения.

---

## Изменение ссылок кнопок «Publish» и «View»

Ссылки кнопок управляются из файла **`js/main.js`**.

Найди в начале файла две переменные и замени значения:

```javascript
const PUBLISH_URL = 'seller.html';  // ← ссылка кнопки Publish
const VIEW_URL    = 'buyer.html';   // ← ссылка кнопки View
```

Сохрани файл — изменения применятся ко всем кнопкам на всех страницах автоматически.

---

## Структура файлов

| Файл | Страница |
|------|----------|
| `index.html` | Главная страница (Home) |
| `seller.html` | Для продавцов (For Seller) |
| `seller-price.html` | Платные услуги (Paid Services) |
| `buyer.html` | Для покупателей (For Buyer) |
| `contacts.html` | Контакты (Contacts) |
| `policy.html` | Политика конфиденциальности (Policy) |
| `css/style.css` | Все стили |
| `js/main.js` | Скрипты (ссылки кнопок, ползунок) |
| `README.md` | Этот файл |

## Медиафайлы

Все изображения, иконки и тексты расположены в папке `media-files/` (скопировать из Google Drive):

```
media-files/
├── map.png
├── logo.png
├── images/
├── icons/
│   ├── solid/
│   ├── regular/
│   └── brands/
└── texts/
```

---

## Технологии

- Чистый HTML5, CSS3, JavaScript (без фреймворков)
- Адаптивная верстка (mobile / tablet / desktop)
- Двухуровневая навигация — только CSS, без JS
- FAQ-аккордеон через `<details>` / `<summary>`
- Интерактивный прайс-лист с `<input type="range">`
