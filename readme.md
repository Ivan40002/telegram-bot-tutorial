# Telegram Bot Tutorial

### Описание

Этот репозиторий содержит в себе несколько ботов для мессенджера Telegram.
Каждый из них предназначен, чтобы показать вам функционал мессенджера.

Каждый бот лежит в своей директории, ниже описание:

- *showroombot* - бот туториал, показывает возможности Telegram в области взаимодействия с пользователем: команды, кнопки, работа с файлами.
- *likebot* - образец inline-бота. Такие боты могут модифицировать содержимое сообщения, которое вы отправляете в канал или группу.
Именно этот бот позволяет добавлять под каждый пост кнопки лайк/дизлайк, чтобы собирать реакцию аудитории вашего канала.
  
- *templatebot* - основа бота, которую можно использовать для разработки вашего собственного бота.

### Инструменты

Для написания ботов используем Python версии 3.6 и выше.

Для взаимодействия с API Telegram используется библиотека [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

Больше различных примеров ее применения вы можете найти [здесь](https://github.com/python-telegram-bot/python-telegram-bot/tree/master/examples)


### Как это работает?

Сначала подготовим окружения для работы:

- Установим virtualenv, если его у вас еще нет:
`pip install virtualenv`
  
- Создадим виртуальное окружение:
`virtualenv venv`
  
- Активируем его:
`source venv/bin/activate`
  
- Установим необходимые зависимости:
`pip install -r requirements.txt`
  
### Материалы мастер-класса
[Можно найти в Telegram канале tbotshowroom](https://t.me/tbotshowroom)
