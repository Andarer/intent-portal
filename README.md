Intent Portal

Минималистичный портал для тестирования Android Intent-ссылок, Deep Links и поведения браузеров/WebView.

---

Что такое Intent Portal?

Intent Portal — это лёгкий web-проект для тестирования:

- Android Intent Links
- Deep Links
- "intent://"
- "android-app://"
- пользовательских URI-схем
- запуска приложений через браузер
- поведения Android WebView
- совместимости браузеров Android

Проект специально сделан максимально простым:

- чистый HTML
- минимальный CSS
- Jekyll
- GitHub Pages

Без:

- React
- npm
- сборщиков
- JavaScript-фреймворков
- сложной инфраструктуры

Только простые и надёжные ссылки для реального тестирования Android.

---

Для чего нужен этот проект?

Современный Android ведёт себя по-разному в зависимости от:

- браузера
- WebView
- оболочки производителя
- версии Android
- системных ограничений

Одна и та же ссылка может:

- работать в Chrome
- не работать в Firefox
- блокироваться Telegram Browser
- иначе открываться в WebView

Intent Portal позволяет быстро проверять всё это на практике.

---

Что можно тестировать?

Intent-ссылки

Пример:

intent:#Intent;action=android.settings.SETTINGS;end

---

android-app ссылки

Пример:

android-app://com.android.settings

---

Deep Links приложений

Примеры:

tg://resolve?domain=telegram

vnd.youtube://

spotify://

---

Возможности проекта

- тестирование Android Intent Links
- проверка Deep Links
- запуск приложений через браузер
- исследование ограничений Android
- тестирование WebView
- создание Android dashboard-порталов
- основа для WebView APK
- оффлайн Android-панели

---

Почему Jekyll?

Jekyll идеально подходит для подобных проектов:

- работает быстро
- не требует базы данных
- отлично дружит с GitHub Pages
- легко редактируется даже с телефона
- можно запускать полностью локально

---

Технологии

- Jekyll
- GitHub Pages
- HTML5
- CSS3

---

Структура проекта

intent-portal/
├── _config.yml
├── index.md
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    └── style.css

---

Установка

1. Установить JekyllEx

Официальный сайт:

https://jekyllex.xyz

Или через F-Droid:

https://f-droid.org/packages/xyz.jekyllex/

---

2. Создать проект

Внутри JekyllEx:

- New Project
- Blank Project
- Название проекта:
  "intent-portal"

---

3. Скопировать файлы проекта

Заменить файлы проекта содержимым репозитория.

---

4. Запустить локальный сервер

Через кнопку:

▶ Serve

или через терминал:

bundle exec jekyll serve

---

5. Открыть локальный адрес

http://127.0.0.1:4000

---

Публикация через GitHub Pages

GitHub:

Settings → Pages

Настройки:

- Branch: "main"
- Folder: "/ (root)"

После публикации сайт будет доступен по адресу:

https://USERNAME.github.io/intent-portal/

---

Совместимость браузеров

Браузер| Совместимость
Chrome Android| Отличная
Android WebView| Отличная
Firefox Android| Частичная
Telegram Browser| Ограниченная
OEM браузеры| Зависит от прошивки

---

Важные замечания

Некоторые версии Android могут ограничивать:

- запуск системных Intent
- открытие приложений
- переходы между приложениями
- работу внешних URI-схем

Особенно:

- Android 12+
- Android 13+
- Android 14+

Поведение может отличаться в зависимости от устройства и браузера.

---

Идеи для развития

- PWA-режим
- WebView APK
- Android Dashboard
- Intent Compatibility Matrix
- логирование результатов
- оффлайн-портал
- Android launcher interface
- системная web-панель

---

Философия проекта

Web — это не только сайты.

На Android web может стать:

- интерфейсом
- панелью управления
- launcher-системой
- связующим слоем между приложениями
- оболочкой поверх Android

Intent Portal исследует именно эту идею.

---

Лицензия

MIT License
