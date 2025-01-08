# Авторизация посетителей на вашем сайте
Что нужно чтобы всё заработало:

в `main.py` вписать все что нужно для работы с авторизацией:

```
app.jinja_env.globals.update(BOTID = REQUIRED) #айди бота из токена до знака :
app.jinja_env.globals.update(BOTNAME = REQUIRED) #имя вашего бота с приставкой bot в конце
app.jinja_env.globals.update(BOTDOMAIN = REQUIRED) #домен вашего сайта из /setdomain в BotFather (обычно http://127.0.0.1:5000)
```

Поменяйте домен сайта на `http://127.0.0.1:5000` в BotFather через `/setdomain`

Установите Flask: `cmd` `>>` `pip install flask`

Когда вы уже поставите свой сайт на домен - не забудьте поменять домен сайта в BOTDOMAIN и в BotFather
