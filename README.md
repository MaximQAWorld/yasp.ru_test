# yasp.ru_test
Тестовое задание — Restful Booker API

Сервис: https://restful-booker.herokuapp.com (документация: /apidoc/index.html)

Состав репозитория
testcases.xlsx — позитивные и негативные тест-кейсы для эндпоинтов: /auth, /booking (POST), /booking (GET с фильтрами), /booking/:id (GET/PUT/PATCH/DELETE), /ping. Лист Summary — сводная статистика по количеству кейсов на эндпоинт.
Restful-Booker.postman_collection.json — коллекция Postman (Collection v2.1), тест-кейсы перенесены в виде запросов с проверками во вкладку Tests (скрипты pm.test). Коллекция построена таким образом, что ее можно обработать целиком: /auth сохраняет токен в переменной коллекции token, POST /booking сохраняет bookingId, используемый в последующих запросах.
bug_report.xlsx — баг-репорт по дефектам, обнаруженным в ходе анализа API и тестирования.

