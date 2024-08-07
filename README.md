# discord-botЧтобы сделать описание бота более привлекательным и оживленным, можно добавить эмодзи и более структурированный формат. Вот пример:

---

# 🤖 Discord Бот с Экономикой Эликсиров 💰

## Описание 📋

Этот Discord бот предоставляет увлекательный опыт для пользователей, включающий экономику "эликсиров", покупку ролей и автоматическую модерацию. Бот построен с использованием библиотеки `discord.py` и хранит данные в базе данных SQLite.

### Функции ✨

- **Экономика Эликсиров** 💸: Пользователи зарабатывают эликсиры, отправляя сообщения. Эти эликсиры можно тратить на роли или специальные права.
- **Автоматическая Модерация** 🛡️: Бот следит за соблюдением правил сервера, выдавая предупреждения и мьюты за спам, рекламу и политические обсуждения.
- **Магазин Ролей** 🛒: Пользователи могут покупать роли за эликсиры.
- **Команды Управления** 🔧: Команды для изменения ника, перевода эликсиров, и выдачи временных ролей.

### Установка и Настройка ⚙️

#### Требования 📚

- Python 3.8 или выше
- Discord.py библиотека
- SQLite3

#### Установка библиотек 🛠️

Установите необходимые библиотеки, выполнив следующие команды:

```sh
pip install discord.py
pip install sqlite3
```

#### Конфигурация 📝

Замените следующие переменные в коде на ваши значения:

- `OWNER_USER_ID`: ID владельца, которому даются бесконечные эликсиры.
- `CENWHOCBWIEHC`: ID пользователя, который имеет доступ к команде `!chikibanbony12`.
- `MUTE_LOG_CHANNEL_ID`: ID канала для отправки сообщений о мьютах.
- `GUILD_ID`: ID вашего сервера.

### Запуск Бота 🚀

Создайте файл с кодом бота (например, `bot.py`) и вставьте туда полный код. Запустите бота командой:

```sh
python bot.py
```

---

