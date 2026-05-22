# Сайт Ольги Китляш — kitliash.github.io

Сайт-визитка косметолога-эксперта Ольги Китляш.

## Структура

```
/
├── index.html        ← единственный HTML-файл
├── images/
│   ├── olga-hero.jpg       ← герой (портрет в чёрной форме)
│   ├── olga-about.jpg      ← раздел «О себе» (белая форма, перчатки)
│   ├── olga-pro.jpg        ← раздел «Для коллег» (с ноутбуком)
│   ├── book-cover.jpg      ← обложка книги «Скин-система»
│   ├── book-contents.jpg   ← содержание книги
│   ├── book-intro.jpg      ← введение книги
│   ├── result-1.jpg        ← результат до/после (акне)
│   ├── result-2.jpg        ← результат до/после (акне, side-by-side)
│   ├── result-3.jpg        ← результат до/после (в кабинете)
│   └── result-4.jpg        ← результат до/после (акне)
└── README.md
```

---

## Деплой на GitHub Pages — пошаговая инструкция

### Шаг 1. Создайте репозиторий на GitHub

1. Перейдите на [github.com](https://github.com) → **New repository**
2. Название: `kitliash` (тогда сайт будет на `https://ВАШ_ЛОГИН.github.io/kitliash/`)
   — **или** назовите `ВАШ_ЛОГИН.github.io` (тогда сайт на корневом адресе без подпапки)
3. Видимость: **Public**
4. Нажмите **Create repository**

### Шаг 2. Загрузите файлы

**Вариант А — через браузер (проще):**
1. Откройте созданный репозиторий
2. Нажмите **Add file → Upload files**
3. Загрузите `index.html`
4. Создайте папку `images` через **Add file → Create new file**, введите `images/.gitkeep` и сохраните
5. Зайдите в папку `images` → **Add file → Upload files**, загрузите все 10 фотографий

**Вариант Б — через Git (если установлен):**
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/ВАШ_ЛОГИН/ИМЯ_РЕПО.git
git push -u origin main
```

### Шаг 3. Включите GitHub Pages

1. Откройте репозиторий → **Settings** (вкладка сверху)
2. В левом меню → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main**, папка: **/ (root)**
5. Нажмите **Save**
6. Через 1–2 минуты сайт появится по адресу, указанному в этом же разделе

---

## Контакты на сайте

- **Телефон:** +7 921 359 23 28
- **Telegram:** @olga_kitlyash
- **TG-канал:** t.me/kitliash
- **Instagram:** @kitliash.cosmo

---

## Добавление в портфолио

Этот сайт — живой пример работы для кейса в портфолио разработчика.
После деплоя ссылку добавить в карточку проекта «Сайт-визитка косметолога».
