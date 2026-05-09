# 🗺️ INTENT-PORTAL ROADMAP

Meta-архитектура развития системы анализа поведения ссылок.

---

## 🧱 ЭТАП 1 — FOUNDATION (ЗАВЕРШЁН / СТАБИЛИЗАЦИЯ)

✔ GitHub Pages структура  
✔ Jekyll система  
✔ базовый index.md  
✔ Intent Lab стартовая версия  

---

## 🧪 ЭТАП 2 — INTENT LAB (ACTIVE)

Цель: создание среды тестирования ссылок

### Функции:
- тест `https://`
- тест `intent://`
- тест deep links:
  - tg://
  - vnd.youtube://
- ручной анализ переходов

### Результат:
Экспериментальная зона поведения ссылок

---

## 📊 ЭТАП 3 — INTENT MATRIX (CORE SYSTEM)

Цель: построение карты поведения платформ

### Среды:
- Chrome
- Firefox
- Android WebView
- Telegram
- Android System Browser

### Структура:
- matrix/index.md
- matrix/chrome.md
- matrix/webview.md
- matrix/firefox.md
- matrix/telegram.md

### Data Layer:
- data/matrix.json (единый источник правды)

---

## 📱 ЭТАП 4 — ANDROID WEBVIEW APK

Цель: превращение портала в приложение

### Возможности:
- загрузка GitHub Pages
- перехват intent://
- логирование переходов
- debug режим анализа
- переключение режимов:

  - WEB MODE
  - INTENT DEBUG
  - MATRIX VIEW

---

## 🧬 ЭТАП 5 — DATA ENGINE (MATRIX.JSON)

Цель: сделать систему управляемой данными

### Функции:
- хранение всех ссылок
- описание поведения платформ
- основа для генерации страниц
- будущая аналитика переходов

---

## ⚙️ ЭТАП 6 — META GENERATION ENGINE

Цель: автоматизация системы

### Возможности:
- генерация HTML/MD страниц из JSON
- добавление новых платформ без ручного кода
- масштабирование матрицы
- единая логика данных

---

## 🚀 ФИНАЛЬНАЯ ЦЕЛЬ

> Intent Portal = Meta Intent Operating Layer

Система, которая:

- анализирует поведение ссылок
- сравнивает цифровые среды
- фиксирует различия между браузерами и приложениями
- формирует карту цифровой реакции систем

---

## 📡 СТАТУС ПРОЕКТА

- Версия: v2.0 Meta Expansion
- Состояние: Active Development
- Архитектура: Modular + Data-driven
