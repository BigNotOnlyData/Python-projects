# Телеграм бот

## Заметки
+ Бот написан на фреймворке [Aiogram](https://docs.aiogram.dev/en/latest/).
+ Для конвертации ауди файла в текст использована библиотека [speech_recognition](https://pypi.org/project/SpeechRecognition/).
+ Для конвертации формата .ogg в .wav необходима установленная программа [ffmpeg](https://ffmpeg.org/)

## Функционал:
+ Бот переводит голосовые сообщения в текст
+ Отвечает пользователю, если сумел определить намерение
+ Выводит вероятность наиболее токсичных сообщений


## Cтруктура бота

+ Файл запуска бота - app.py
+ Предобученные модели в data\models
+ Валидные интенты в data\intents\BOT_CONFIG_INTENTS.json
+ Логика обработки сообщений в handlears\users\
