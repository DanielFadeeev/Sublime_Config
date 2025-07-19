# 🐍 Sublime Text 4 — Конфиг для Python (Windows)

> Настройка редактора кода под язык Python c линтингом, автоформатом и встроенным терминалом

---

## 🚀 Что настроенно?

1. ✅ LSP и pylsp — полноценное автодополнение
2. ✅ AutoPEP8 и Black — автоформатирование 
3. ✅ Terminus — терминал внутри редактора 
4. ✅ Темы, иконки, горячие клавиши 
---

## 📦 Плагины

**Базовые:**
- `Base16 Color Schemes` — тема Ocean
- `BracketHighlighter` — подсветка скобок  
- `SideBarEnhancements` — расширенное меню
- `A File Icon` — иконки файлов  
- `ColorHighlighter` — цвет в коде

**Python:**
- `LSP`
- `LSP-pylsp`
- `AutoPEP8`
- `TabNine`
- `Terminus`

---

## 🔥 Горячие клавиши

* `F5` — запуск скрипта
* `Ctrl + Shift + F` — форматирование
* `F12` — перейти к определению
* `Shift + F12` — найти все вхождения
* `Ctrl + .` — действия LSP
* `Ctrl + Shift + T` — терминал

---

## ⚙️ Установка

### 1. Установи Sublime Text 4  
[https://www.sublimetext.com/](https://www.sublimetext.com/)

### 2. Установи Package Control  
`Ctrl + Shift + P` → "Install Package Control" → Enter → перезапуск

### 3. Установи Python и pip  
[https://www.python.org/downloads/](https://www.python.org/downloads/)  
Поставь галочку "Add Python to PATH"

### 4. Установи Python пакеты:

```bash
pip install python-lsp-server[all] python-lsp-black ruff black
