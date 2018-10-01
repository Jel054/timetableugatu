# timetableugatu
Telegram бот, который парсит сайт с расписанием УГАТУ. Мне очень жаль, что вы это видите, отвернитесь

## Зависимости
* Python 3.7+ (после последнего изменения сайта я рассчитываю на упорядоченный dict. В теории должно работать и на 3.6, но как фича это заявлено в 3.7. Вероятно в requests можно всунуть и не dict (например OrderedDict), но времени у меня не было)
* python-telegram-bot
* pytz
* redis
* BeautifulSoup4
* lxml

## Установка
1. Установите все библиотеки из списка выше через pip:
```
pip3 install --upgrade python-telegram-bot pytz redis BeautifulSoup4 lxml
```
2. С помощью [@BotFather](https://t.me/BotFather) создайте [нового бота](https://core.telegram.org/bots#6-botfather)
3. Подставьте в код полученный токен (а лучше воткните туда os.environ)
4. Установите [redis](https://redis.io/), пароль и IP тоже воткните в код
5. Запускайте
`python3 bot.py`

## Использование
Повернитесь на бок, постарайтесь не плакать, много плачьте
