# goit-nodejs-hw-01

## Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
![Screenshot 1](https://ibb.co/XY9jpgw)

## Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
![Screenshot 2](https://ibb.co/f9SxqTT)

## Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
![Screenshot 3](https://ibb.co/KDtvfFD)

## Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
![Screenshot 4](https://ibb.co/K6mD2y2)
