![Lab](./img/SingletonUML.png)


Пояснення:
Одинак забезпечує існування лише одного екземпляра DocumentManager та надає глобальну точку доступу до нього.
Безпека потоку (thread safety) використовує блокування (lock) для забезпечення потокобезпечного створення єдиного екземпляру.
Клас DocumentManager:
Методи: Створення, редагування та розповсюдження документів.
Приватний конструктор: Запобігає прямому створенню екземплярів.
Статична властивість екземпляра: Надає доступ до єдиного екземпляра.
Використання у Main:
Отримує доступ до єдиного екземпляра DocumentManager.
Створює, редагує та розповсюджує документи.
Перевіряє, що існує лише один екземпляр.

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Z0eBgHwz)
# Патерн одинак (Singleton)

- Потрібно вивчити теоретичний матеріал та написати власноруч приклад коду для патерну sigleton.
- Закомітити даний приклад та зробити pull request.
- Згідно власного варіанту потрібно переписати існуючий проект та додати за потреби нові класи. Варіанти завдань отримати у викладача.
- В README файлі навести UML діаграму класів для коду згідно власного варіанту з короткими поясненнями.
- Закомітити код та зробити pull request.

## Варіанти індивідуальних завдань
14. Створити Singleton для системи документообігу, що забезпечує централізований доступ до створення, редагування та розподілу документів в організації.

