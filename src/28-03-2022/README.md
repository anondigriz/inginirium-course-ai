# Создание чат-бота с применением нейронных сетей

## Используемые решения

Здесь представлен перечень используемых решений:

* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot/)
* [AIOGram](https://github.com/aiogram/aiogram)

## Полезные ресурсы

Здесь представлен перечень полезных ресурсов:

* Асинхронное программирование в [Python](https://tproger.ru/translations/asynchronous-programming-in-python/)
* Всё, о чём должен знать разработчик [Телеграм-ботов](https://habr.com/ru/post/543676/)
* How to build and deploy a Telegram bot with [Flask](https://blog.logrocket.com/build-deploy-telegram-bot-with-flask/)
* Telegram bot with [Flask](https://danielmg.org/python/2021/01/telegram-bot-with-flask.html)
* Webhooks [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot/wiki/Webhooks)
* Простой Telegram-бот на Flask с информированием о [погоде](https://habr.com/ru/post/495036/)
Telegram bot tutorial using python and [flask](https://aliabdelaal.medium.com/telegram-bot-tutorial-using-python-and-flask-1fc634da9522)

## Самостоятельная работа

Необходимо создать бот для Telegram, взаимодействующий с Telegram через Polling и использующий нейронную сеть. Модель нейронной сети необходимо выбрать на свое усмотрение из моделей, которые рассматривались на [занятии 26-03-2022](src/26-03-2022/README.md) (предварительно обученная MobileNetV2 или трансферно обученная модель MobileNetV2 для датасета "Цветы"). Полученное приложение выгрузить в репозиторий GitHub.

**Внимание**: будьте осторожны при выгрузке вашего проекта в открытый репозиторий. Необходимо убедиться, что вы не выкладываете в открытый секретную информацию, например, доступ токен бота. Убедитесь, что у вас в `.gitignore` указана папка `.vscode`.
