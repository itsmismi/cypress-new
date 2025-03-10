<h2>UI Автотесты на фреймворке Cypress</h2>

> **Статус проекта:**
> Публичный проект: https://login.qa.studio/
> 
> 🟢 Поддерживается (активный) 

## Описание проекта и задачи
Автоматизировать часть проверок регресса с помощью Cypress

## Тест-кейсы, которые автоматизировали
* Авторизация с верным паролем и верным логином
* Авторизация c верным логином и неверным паролем
* Проверка работы валиадации на наличие @ в логине
* Проверка флоу восстановления пароля

## Детали реализации

1. baseUrl вынесен в переменные конфига
![image](https://raw.githubusercontent.com/itsmismi/cypress-new/refs/heads/main/base_url.png)

2. Применение хуков beforeEach и afterEach
![image](https://raw.githubusercontent.com/itsmismi/cypress-new/refs/heads/main/bef.png)

3. Переменные данные для авторизации вынесены в отдельный файл
![image](https://raw.githubusercontent.com/German-D/new_cypress/main/static/user_data.png)

4. Каждая страница описана в формате объекта с локаторами
![image](https://raw.githubusercontent.com/itsmismi/cypress-new/refs/heads/main/locators.png)

## Локальный запуск через Cypress UI
1. Скачать проект и открыть в терминале.
2. Перейти в директорию проекта.
3. В терминале в папке с проектом запустить npm `install --save-dev cypress@12.7.0`
4. В терминале в папке с проектом запустить npm `npm i`
5. В терминале в папке с проектом запустить npm `npx cypress open`
6. Выбрать в Cypress UI E2E тестирование и браузер Google Chrome
7. Выбрать спеку misha

Ожидаемый результат: получим отчет о прохождении тестов.
![image](https://raw.githubusercontent.com/itsmismi/cypress-new/refs/heads/main/end.png)


## Автор

Михаил Смирнов ([@smirnov](https://t.me/itsmismi))
