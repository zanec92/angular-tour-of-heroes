# Tour Of Heroes App

Курс по Angular "Tour Of Heroes App"(https://angular.io/tutorial). Редактор героев.

## Установка и запуск приложения

Для установки и запуска проекта нужно выполнить следующие команды в корневой директории проекта:

> **npm install**

> **ng serve** (не закрывать окно с данной командой)

После этого проект будет доступен по адресу http://localhost:4200.

# Функционал и возможности приложения

## **Вывод списка героев**
Вывод списка героев осуществлен на странице http://localhost:4200/heroes.
Имеется панель навигации, а также компонент логов "Messages".

![Вывод списка героев](https://github.com/zanec92/angular-tour-of-heroes/blob/master/README_images/screenshot2-1.png)

---------------------------------------

## **Добавление новых героев**
Добавление новых героев доступно по адресу http://localhost:4200/heroes.
При нажатии на кнопку "Add" идет post-запрос к In-Memory Web Api для добавления героя во временное хранилище.

![Добавление новых героев](https://github.com/zanec92/angular-tour-of-heroes/blob/master/README_images/screenshot3-1.png)

---------------------------------------

## **Поиск героев**
Поиск героев доступен на странице http://localhost:4200/dashboard.
Поиск выполняется после ввода нового символа в поле "Hero Search". Запрос осуществляется после 300ms с события ввода нового символа. Дублированные запросы не выполняются.

![Поиск героев](https://github.com/zanec92/angular-tour-of-heroes/blob/master/README_images/screenshot4-1.png)

---------------------------------------

## **Псевдотоп**
Псевдотоп создан при помощи простого slice() массива с героями. Добавлен просто для ознакомления с Angular.

![Псевдотоп](https://github.com/zanec92/angular-tour-of-heroes/blob/master/README_images/screenshot1-1.png)

---------------------------------------


## **Также**
- Удаление героев
- Редирект с главной страницы на Dashboard
- Асинхронные запросы к In-Memory Web Api(https://github.com/angular/in-memory-web-api).

