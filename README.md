# merci
Cервис изменения баланса бонусов клиента

Инструкция по запуску
1. Сборка образа(точка в конце на след строке это часть команды)
docker build -t merci .
2. Запуск образа
docker run -dp 8075:8075 merci