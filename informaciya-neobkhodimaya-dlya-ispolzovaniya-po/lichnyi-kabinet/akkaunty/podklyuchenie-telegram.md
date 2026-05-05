# Подключение Telegram

## Для чего нужно подключать Telegram?

В личном кабинете на вкладке "Аккаунты" по кнопке "Подключить Telegram каналы" вы можете подключить Telegram каналы или группы для отложенного постинга в них.

## **Как подключить Telegram?**

**1. Создайте бота**

Откройте приложение Telegram. Найдите бота с ником [@botfather](https://t.me/botfather) и напишите ему сообщение /newbot.

![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2FbAARcUxHh6VLzMiGXytz%2FIMG_0776.png?alt=media\&token=79e8bb05-828e-4eb1-806c-5522a834223c)

Botfather спросит название и имя вашего бота. Имя должно заканчиваться на ...bot или ...Bot.

![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2FGavrB1qMye4BcjJefa9u%2FIMG_0778.png?alt=media\&token=7af0b8e9-74e1-4bbd-a294-fcd8b75d0138)

Botfather пришлет токен вашего бота. Его необходимо скопировать и вставить в поле "Токен бота".

**2. Добавьте бота в администраторы канала**

Добавьте только что созданного бота в администраторы вашего канала.

![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2FqWYtGP7wvectTRqOjE2u%2FIMG_0783.png?alt=media\&token=96a81642-7daf-49b4-88d8-88f662f409d9) ![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2FD0jDcXN2yhe3CDjRzc9s%2FIMG_0780.png?alt=media\&token=b29a55e1-80fc-458f-b267-5589288fdc6b) ![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2FvdQxTf2tdAElSSdVXcmb%2FIMG_0781.png?alt=media\&token=3812c320-b44d-49f1-8b10-7f677acbc621) ![](https://1243024340-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MTYe3w_ypVECLKrTuXb%2Fuploads%2F39UTgVNulXdJ4LBPKK6f%2FIMG_0782.png?alt=media\&token=cfd2fbb0-41a2-40e1-bb96-d88d8059bf4f)

**3. Подключение канала**

Ссылку на канал необходимо скопировать и вставить в поле "Ссылка на канал".

***

## **Как подключить частный канал?**

> Идентификатор недоступен для обычного пользователя – в адресной строке вы не увидите цифровых обозначений. Но их можно получить, используя дополнительные инструменты. В этом могут помочь боты.

Чтобы подключить частный канал нужно узнать id канала:

1. Пригласите своего созданного бота (которого вы создали в боте BotFather) и добавьте в администраторы канала.
2. Находим бота @myidbot (IDBot).
3. Теперь пересылаем из частного канала какую-нибудь публикацию боту @myidbot. Это может быть абсолютно что угодно.
4. Бот IDBot ответит вам, переслав идентификатор «ID of channel» будут нужные цифры (Id канала с минусом). Да, он начинается с минуса. Не удивляйтесь, для каналов это совершенно нормально.
5. Скопировать id (все что после ID of channel: со знаком минусом).
6. Вставить этот id в поле Ссылка на канал на сервисе.

***

## **Как подключить частную группу?**

> Идентификатор недоступен для обычного пользователя – в адресной строке вы не увидите цифровых обозначений. Но их можно получить, используя дополнительные инструменты. В этом могут помочь боты.

Чтобы подключить частную группу инужно узнать id группы:

1. Пригласите своего созданного бота (которого вы создали в боте BotFather) и добавьте в администраторы канала.
2. Находим бота @myidbot (IDBot).
3. Приглашаем бота @myidbot (IDBot) в нашу частную группу.
4. Теперь отправляем в нашу группу сообщение /getgroupid и получаем ответ от бота.
5. Бот IDBot ответит вам, переслав идентификатор вашей группы «Your supergroup ID is». Да, он начинается с минуса. Не удивляйтесь, для групп это совершенно нормально.
6. Скопировать все, что идет после Your supergroup ID is: (с минусом)
7. Вставить этот id в поле Ссылка на канал на сервисе.
