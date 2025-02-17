# Децентрализованное приложение для голосования 

Распределенное приложение для проведения электронного голосования.  

Проект содержит фронтенд и демонстрацию основных возможностей по созданию и тестированию смарт-контрактов с помощью библиотеки [Hardhat](https://hardhat.org/).

## Структура проекта

Проект включает в себя три директории: 

1. `/scripts` - скрипты для голосования
2. `/contracts` - исходный код смарт-контракта на языке `Solidity`
3. `/tests` - локальные тесты смарт-контракта

## Установка

Клонируйте репозиторий и установите зависимости из корневого каталога командой `npm install`.
После  установки `hardhat` вы можете скомпилировать и протестировать смарт-контракт локально, без подключения к сети Ethereum. 
Справку по командам `hardhat` можно получить командой `npx hardhat help`.

## Компиляция смарт-контракта
Скомпилируйте контракт командой `npx hardhat compile`. 
Артифакты (результаты компиляции) будут размещены в папке с файлами фронтенда `/app`.
Параметры компиляции можно настроить в файле  `hardhat.config.js`.

В качестве упражнения выполните следующие команды: 

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
