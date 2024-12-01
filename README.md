# Сервис визуализации организационной структуры

## Описание проекта

Этот сервис позволит сотрудникам легко ориентироваться в иерархии, быстро находить сотрудника по его роли,
проекту, должности и многим другим критериям. Удобный интерфейс приложения и эффективный встроенный по-
иск облегчат межличностное взаимодействие, сделав процессы работы в компании более прозрачными
и доступными для всех сотрудников.

## Запуск проекта
Для frontend части:
```
Установить зависимости: npm install

Запустить frontend: npm run dev

Открыть приложение в браузере: http://localhost:5173

Используемая версия Node - v20.9.0
```
Для backend части:
```
Установить SSMS

В папке dbshka находится .bak-файл - это бэкап базы данных.

Подключиться к локальной базе.

В Object Explorer нажать правой кнопкой мыши на папку Databases.

Затем Выбрать опцию 'Restore database', там выбрать Device и в меню на кнопке "..." указать буть к файлу .bak
"Ok"
```


---

В этом проекте используется [`next/font`](https://extjs.org/docs/basic-features/font-optimization) для автоматической оптимизации и загрузки пользовательского шрифта Google Inter.

## Скрипты

- `npm run dev` - Запуск React.js в режиме разработки
- `npm run start` - Запуск React.js в рабочем режиме
- `npm run build` - Сборка

## Архитектура проекта

Проект написан в соответствии с методологией Feature sliced design.

Ссылка на документацию - [feature sliced design](https://feature-sliced.design/docs/get-started/tutorial)

---

## Линтинг

В проекте используется prettier для проверки кода.

## Участники
### Заббаров Эмиль
- Анализ данных
- Создание дизайна
### Ярлыкова Юлия 
- Верстка
- Интеграция
### Абдурахипов Роман
- Верстка
- Интеграция
### Кривенко Егор
- Написание кода сервера
- Создание бд
