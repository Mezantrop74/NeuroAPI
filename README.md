# NeuroGPT - Бесплатный доступ к ChatGPT 3.5 / 4 / Claude 2

Данный проект позволяет пользоваться ChatGPT и Claude без VPN и регистрации аккаунта. 

## Поддерживаются модели:

- ChatGPT-3.5-Turbo
- ChatGPT-3.5-Turbo-0613
- ChatGPT-3.5-Turbo-16K
- ChatGPT-3.5-Turbo-16K-0613
- GPT-4 (Нужен ключ ChimeraAPI)
- Sage (Нужен ключ ChimeraAPI)
- Claude Instant (Нужен ключ ChimeraAPI)
- Claude Instant 100K (Нужен ключ ChimeraAPI)
- Claude 2 (Нужен ключ ChimeraAPI)

## Возможности программы:

- Веб поиск
- Джейлбрейки для расширения возможностей и снятия цензуры
- Контекст беседы
- Режим endpoint для работы с API
- Тонкая настройка модели (ChatGPT)
- Сохранение и загрузка истории диалогов

## Портативная версия

Портативную версию, не требующую установку зависимостей и запускающуюся в 1 клик можно скачать тут. 

## Поддержка и вопросы

Если у вас возникли какие то вопросы или вы в принципе хотите обсудить проект, то это можно сделать в моем телеграм канале: https://t.me/neurogen_news

Поддержать автора, подкинув на кофе, можно тут: [DonationAlerts](https://www.donationalerts.com/r/em1t)

# ChimeraAPI - как пользоваться:

Это проект, предоставляющий бесплатный доступ через reverse-API к различным моделям ChatGPT и Claude. 
На использование ChatGPT есть лимиты, которые, впрочем, достаточны для обычного пользователя:

GPT-4 8K - 10 запросов в минуту / 1000 в день

GPT-3.5-TURBO - 20 / 2000

GPT-3.5-TURBO 16K - 20/2000

Чтобы работать с ним, вам надо получить их API ключ.
1) Вступаем в Discord проекта (https://discord.gg/chimeragpt), проходим верификацию (https://discord.com/channels/1109383423061147680/1110612696874885141), идем в канал #bot и отправляем команду /key get
2) Полученный ключ записываем в config.json файл, который лежит в той же папке, где и bat файл для запуска чата
3) Меняем строку openai_api_key="ваш_api_код" на ваш код
4) Пользуемся ChimeraAPI моделями
