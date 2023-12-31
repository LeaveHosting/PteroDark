# PteroDark

## Мова
- [English](README.md)
- [Українська](READMEUK.md)
- [Русский](READMERU.md)


## ПОПЕРЕДЖЕННЯ: бібліотека знаходиться на стадії розробки і може не працювати, як описано нижче

PteroDark — це бібліотека Python, яка служить оболонкою API для панелі Pterodactyl.  Він надає простий і зручний спосіб взаємодії з Pterodactyl API і керування вашими ігровими серверами.

## ~~Особливості~~

- ~~Автентифікація та керування маркерами API~~
- ~~Отримайте інформацію про сервери, користувачів і вузли~~
- ~~Створення, оновлення та видалення серверів~~
- ~~Запуск, зупинка, перезапуск і перевстановлення серверів~~
- ~~Керуйте файлами та каталогами сервера~~
- ~~Виконуйте команди на серверах~~
- ~~І багато іншого!~~

## Встановлення 

Щоб встановити PteroDark, просто використовуйте pip:

```bash
pip install PteroDark
```

## ~~Використання~~

~~Ось простий приклад того, як використовувати PteroPy для взаємодії з Pterodactyl API:~~

```python
import PteroDark

# Створіть екземпляр клієнта
client = PteroDark.Client(api_url='https://your-panel-url.com', api_key='your-api-key')

# Отримати інформацію про сервер
server_info = client.get_server_info(server_id='your-server-id')
print(server_info)

# Запустіть сервер
client.start_server(server_id='your-server-id')

# Виконати команду на сервері
output = client.send_command(server_id='your-server-id', command='say Hello, server!')
print(output)
```

~~Щоб отримати детальнішу документацію та приклади, зверніться до [офіційної документації PteroPy](https://github.com/LeaveHosting/PteroPy).~~

## Внески

Внески до PteroDark завжди вітаються!  Якщо у вас є пропозиції, звіти про помилки чи запити щодо функцій, будь ласка, відкрийте проблему або надішліть запит на отримання в [репозиторії GitHub](https://github.com/LeaveHosting/PteroDark).

## Ліцензія

PteroDark ліцензовано згідно з ліцензією MIT.  Див. [ЛІЦЕНЗІЯ](https://github.com/LeaveHosting/PteroDark/blob/main/LICENSE) файл для отримання додаткової інформації.

## Подяки

Особлива подяка команді Pterodactyl за надання чудової панелі та API, які надихнули цю бібліотеку.

Не соромтеся зв’язатися, якщо у вас виникнуть запитання або вам потрібна додаткова допомога.  Щасливого кодування з PteroDark!
