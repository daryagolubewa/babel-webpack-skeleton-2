# Learn Babel for Server and Client

Откройте папку

* 1_server - для примера бабеля на сервере
* или папку 2_client для примера бабеля с вебпаком для браузера.

## Задания

1. Сервер. Выбрать две фичи из ES6+, которые не поддерживаются в node 8 и с помощью babel plugin-ов настроить трансформацию.
2. Сервер. Выбрать три фичи из ES6+, которые не поддерживаются в node 6 и решить это с использованием presets.
3. Браузер. Выбрать две фичи из ES Next и настроить трансформацию через плагины для того чтобы эти фичи работали в последней версии хрома.
4. Браузер. Выбрать две фичи из ES Next и настроить для них поддержку с использованием Polyfill-ов. Для одной из фичей написать свой полифил (достаточно какую-то базовую версию).
5. Перевести один из проектов на использование Babel и Webpack
6. Обновить бабель до 7й версии

## Доп информация

### Установка Node Version Manager (NVM)
```
sudo apt-get install curl
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
command -v nvm
nvm ls-remote
nvm install v8.9.4
node -v
npm -v
node
```

### Ссылки

* https://babeljs.io/
* https://hackernoon.com/polyfills-everything-you-ever-wanted-to-know-or-maybe-a-bit-less-7c8de164e423
* http://kangax.github.io/compat-table/es6/

### Скринкасты от Майкла по теме

* Transpiling vs Polyfilling - https://youtu.be/ScUENgRrAdw
* Server. Babel - https://youtu.be/CR9zozstWzU
* Presets, Plugins, Polyfills - https://youtu.be/2aqwnaUc9DQ
* Browser. Babel - https://youtu.be/DRPEz4d9pKc
