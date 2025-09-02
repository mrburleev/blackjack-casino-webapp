# 🎰 BlackJack Casino - Telegram WebApp

Профессиональная игра в блэкджек для Telegram мини-приложений.

## 🎮 Особенности

- ✅ **Полноценный блэкджек** с правильными правилами
- ✅ **Звуковые эффекты** и тактильная обратная связь
- ✅ **Система статистики** с достижениями
- ✅ **Адаптивный дизайн** для мобильных устройств
- ✅ **Интеграция с Telegram** WebApp API
- ✅ **Красивые анимации** и эффекты

## 🚀 Демо

Игра доступна по адресу: [https://your-username.github.io/blackjack-casino-webapp/](https://your-username.github.io/blackjack-casino-webapp/)

## 🛠️ Технологии

- HTML5
- CSS3 (адаптивный дизайн)
- JavaScript (ES6+)
- Web Audio API (звуки)
- Telegram WebApp API
- LocalStorage (статистика)

## 📱 Интеграция с Telegram ботом

```python
from aiogram.types import WebAppInfo, InlineKeyboardMarkup, InlineKeyboardButton

web_app = WebAppInfo(url="https://your-username.github.io/blackjack-casino-webapp/")
keyboard = InlineKeyboardMarkup(inline_keyboard=[
    [InlineKeyboardButton(text="🎰 Играть в BlackJack", web_app=web_app)]
])
```

## 🎯 Функции игры

### Основная игра
- Правильные правила блэкджека
- Удвоение ставки
- Автоматическая игра дилера
- Подсчет очков с тузами

### Статистика
- Общая статистика игр
- Процент побед
- Серии выигрышей/проигрышей
- Система достижений
- Отслеживание времени игры

### UX/UI
- Красивые анимации карт
- Звуковые эффекты для всех действий
- Фейерверки при выигрыше
- Интуитивные кнопки управления
- Темная тема в стиле казино

## 📄 Лицензия

MIT License - используйте свободно для своих проектов!

---

Создано с ❤️ для Telegram WebApp экосистемы