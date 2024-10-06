[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/BybitCoinsweeper_Bot?start=referredBy=1197825376)
[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/CyberToolz)


# Бот для BybitCoinsweeper



# 🔥🔥 Используйте Python версии 3.10 - 3.11.5 🔥🔥

> 🇪🇳 README in english available [here](README-EN)

## Функционал  
|                   Функционал                   | Поддерживается |
|:----------------------------------------------:|:--------------:|
|Многопоточность              				     |       ✔️       | 
|Привязка прокси к сессии           			 |       ✔️       | 
|Авто-регистрация аккаунта по вашей реф. ссылке  |       ✔️       |
|Авто игра с выбором рандомных поинтов           |       ✔️       |
|Авто таски             				         |       ✔️       |
|Авто YouTube таски            					 |       ✔️       |
|Поддержка pyrogram .session       			     |       ✔️       |


## [Настройки](https://github.com/Cybertat1on/BybitCoinsweeper/Botblob/main/.env-example/)
| Настройки 			     |								Описание 		            					         |
|----------------------------|:-------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Данные платформы, с которой будет запущена сессия Telegram (по умолчанию: android)    |       
| **REF_LINK**               | Ваша реферальная ссылка                          					                 |
| **AUTO_PLAY**              | Авто игра ( по умолчанию: True)                                                       |
| **GAME_PLAY_EACH_ROUND**   | Случайное количество игр в одном раунде (по умолчанию: [2, 4])                        |
| **TIME_PLAY_EACH_GAME**    | Произвольное время в секундах для каждой игры (по умолчанию: [130, 180])              |
| **USE_PROXY_FROM_FILE**    | Использовать ли прокси из файла `bot/config/proxies.txt` (по умолчанию - False)       |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл `run.bat` на **Windows** или `run.sh` на **Линукс**

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/release/python-3100/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [**my.telegram.org**](https://my.telegram.org/auth) и войдите в систему, используя свой номер телефона.
2. Выберите `API development tools` и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/Cybertat1on/BybitCoinsweeper) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/Cybertat1on/BybitCoinsweeper.git
cd BybitCoinsweeper
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/BybitCoinsweeper >>> python3 main.py --action (1/3)
# Or
~/BybitCoinsweeper >>> python3 main.py -a (1/3)

# 1 - Запускает кликер
# 2 - Создает сессию
# 3 - Запускает кликер (Запрос)
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/BybitCoinsweeper >>> python main.py --action (1/3)
# Или
~/BybitCoinsweeper >>> python main.py -a (1/3)

# 1 - Запускает кликер
# 2 - Создает сессию
# 3 - Запускает кликер (Запрос)
```
# Termux manual installation
```
> pkg update && pkg upgrade -y
> pkg install python rust git -y
> git clone https://github.com/Cybertat1on/BybitCoinsweeper.git
> cd BybitCoinsweeper
> pip install -r requirements.txt
> python main.py
```

You can also use arguments for quick start, for example:
```termux
~/BybitCoinsweeper > python main.py --action (1/2)
# Or
~/BybitCoinsweeper > python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session 
```
