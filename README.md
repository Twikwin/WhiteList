# WhiteList
Telegram bot for automated Minecraft whitelist management, player applications and Discord integration.  Telegram-бот для автоматизации управления Minecraft Whitelist, обработки заявок игроков и интеграции с Discord.

@WhiteListPT_bot - Telegram
https://t.me/WhiteListPT_bot - Telegram
# Whitelist Bot

**A Minecraft whitelist management bot for Telegram and Discord.**

Add the bot, and let it handle the rest!

## 🇬🇧 English

### About the Project

Whitelist is a bot designed to simplify and speed up whitelist management for Minecraft servers.

It automates player application processing, whitelist synchronization and communication between administrators and players.

### How It Works

1. A player sends their Minecraft username to the designated group.
2. The bot creates an application card with three buttons:
   - **Accept** — adds the player to the server whitelist.
   - **Reject** — allows an administrator to provide a rejection reason.
   - **Ban** — provides an option to ban a player.
3. After processing, the bot synchronizes the whitelist and notifies the player of the result.

### Minecraft Server Integration

The bot connects to Minecraft servers through the hosting panel API.

This approach is used because ServerTap does not support Minecraft 1.21. It does not require additional open ports.

Configuration includes:
- Hosting panel address
- Client API credentials
- Server ID
- Automatic connection and whitelist verification

### Player Profiles

Each player has an individual profile containing:
- Minecraft username
- Telegram user ID
- Telegram username
- Application status
- Server whitelist status
- Other relevant information

Profiles can be accessed using the `/who` command and a player's ID, Minecraft username or Telegram username.

### Communication System

Administrators can reply directly to forwarded player messages.

The bot forwards the response to the player without revealing which administrator sent it. Messages without a reply remain internal.

### Flexibility and Connectivity

- Move the bot between chats using `/chat`.
- Change the connected Minecraft server through the settings menu.
- Connect Discord.
- Manage server connections through the bot's configuration.

### Reliability

The bot communicates with the hosting panel and server using the available connection infrastructure, allowing it to synchronize whitelist data and verify changes.

### Requirements

- A Minecraft server with hosting panel access.
- Panel API credentials (Client).
- Server connection details and SFTP access.
- Telegram administrator permissions.
- Discord integration (optional).

---

## 🇷🇺 Русский

### О проекте

**Whitelist** — это бот, созданный для упрощения и ускорения управления белым списком (Whitelist) Minecraft-серверов.

Он автоматизирует обработку заявок игроков, синхронизацию вайтлиста и взаимодействие между администраторами и игроками.

### Принцип работы

1. Игрок отправляет свой игровой ник в специальную группу.
2. Бот создаёт карточку заявки с тремя кнопками:
   - **Принять** — добавляет игрока в вайтлист сервера.
   - **Отклонить** — позволяет указать причину отказа.
   - **Бан** — предоставляет возможность заблокировать игрока.
3. После обработки бот синхронизирует вайтлист и уведомляет игрока о результате.

### Подключение Minecraft-сервера

Бот подключается к Minecraft-серверу через API панели хостинга.

Такой способ используется из-за отсутствия поддержки Minecraft 1.21 в ServerTap. Дополнительные открытые порты не требуются.

Для подключения необходимы:
- Адрес панели хостинга.
- Client API Credentials.
- ID сервера.
- Автоматическая проверка подключения и вайтлиста.

### Система профилей

Для каждого игрока создаётся отдельный профиль, содержащий:
- Игровой ник Minecraft.
- ID пользователя Telegram.
- Telegram Username.
- Статус заявки.
- Наличие игрока в вайтлисте сервера.
- Дополнительную информацию.

Профиль можно вызвать командой `/who`, используя ID игрока, игровой ник или Telegram Username.

### Система общения

Администраторы могут отвечать игрокам напрямую через пересланные сообщения.

Бот отправляет ответ игроку от своего имени, не раскрывая личность администратора. Сообщения без Reply остаются внутренней перепиской.

### Гибкость и подключение

- Перенос бота между чатами командой `/chat`.
- Смена подключённого Minecraft-сервера через меню настроек.
- Возможность подключения Discord.
- Управление подключениями через настройки бота.

### Надёжность

Бот взаимодействует с панелью хостинга и сервером через доступную инфраструктуру подключения, что позволяет синхронизировать данные вайтлиста и проверять внесённые изменения.

### Требования

- Minecraft-сервер с доступом к панели управления.
- API-ключ панели (Client).
- Данные подключения к серверу и SFTP.
- Права администратора в Telegram.
- Интеграция с Discord (необязательно).

---

**Whitelist Bot — Simplify your server management.**

**Whitelist Bot — Упростите управление своим сервером.**
