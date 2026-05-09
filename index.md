---
layout: default
title: Intent Portal — Meta System v2
---

# 🧠 INTENT-PORTAL

## Meta System for Intent & Link Behavior Analysis

Система анализа поведения ссылок и intent-схем в разных цифровых средах:

- 🌐 Браузеры (Chrome, Firefox)
- 📱 Android WebView
- 💬 Telegram in-app browser
- 📲 Native Android intents

---

## 🧬 СТРУКТУРА СИСТЕМЫ

---

### 🧪 Intent Lab
Экспериментальная зона тестирования ссылок и intent-схем.

Что здесь происходит:
- проверка `https://` ссылок
- тестирование `intent://`
- проверка deep links (`tg://`, `vnd.youtube://`)
- анализ реакции разных сред

👉 [Открыть Intent Lab](lab/intent-lab.html)

---

### 🧪 Sandbox Browsers (NEW)
Модуль анализа sandbox-ограничений браузеров и execution isolation layer.

Что здесь происходит:
- поведение Chrome sandbox
- ограничения Firefox execution
- WebView sandbox model
- различия между browser / OS слоями

👉 [Открыть Sandbox Browsers](lab/sandbox-browsers.html)

---

### 🔥 Intent Links Sandbox (NEW)
Хард-набор ссылок для стресс-тестирования execution среды.

Проверяется:
- intent:// схемы
- system intents (tel:, mailto:, geo:)
- edge-case URL payloads
- sandbox break сценарии

👉 [Открыть Intent Links Sandbox](lab/intent-links-sandbox.html)

---

### 📊 Intent Matrix
Центральная система сравнения поведения платформ.

Сравниваем:

- Chrome
- Firefox
- Android WebView
- Telegram
- Android System

👉 [Открыть Intent Matrix](matrix/index.html)

---

### 📱 WebView Layer
Модель поведения ссылок внутри Android WebView среды.

👉 [Открыть WebView Layer](matrix/webview.html)

---

### 🌐 Chrome Behavior
Поведение Chrome как execution sandbox среды.

👉 [Открыть Chrome Matrix](matrix/chrome.html)

---

### 🗺️ Roadmap (архитектура системы)

Живая карта развития Intent-Portal.

- этапы разработки
- эволюция системы
- переход к Meta-архитектуре
- планы Android APK + data engine

👉 [Открыть Roadmap](roadmap.md)

---

## 📱 ANDROID INTENT LAYER

Базовая поддержка системных интентов:

### ⚙️ System Intents
- Settings
- Wi-Fi
- Bluetooth
- App Settings

### 🔗 App Schemes
- tg:// (Telegram)
- vnd.youtube:// (YouTube)
- intent:// (Android system)

---

## 🧬 META-ЭВОЛЮЦИЯ

Текущий уровень системы:

### v2.1 → v2.2 Engine Transition

Добавляется:

- JSON data engine (matrix.json)
- генерация страниц из данных
- логика execution comparison
- расширение sandbox layer
- подготовка Android WebView execution model

---

## 🚀 ЦЕЛЬ СИСТЕМЫ

> Создать Meta Intent Operating Layer  
> (систему анализа поведения ссылок в цифровых средах)

---

## 📡 СТАТУС

- Версия: v2.2 (Engine Transition)
- Состояние: Active Development
- Тип: Experimental Meta Execution System
