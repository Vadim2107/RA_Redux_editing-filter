# Домашнее задание к курсу «React: библиотека № 1 в современной фронтенд-разработке»

## RA_Redux_editing-filter

### Редактирование

1. По умолчанию показывается форма добавления (при заполнении и нажатии на кнопку Save) происходит добавление элемента в список.
2. При нажатии на кнопку редактировать форма автоматически заполняется данными элемента.

Далее возможны два сценария:

2.1 Если пользователь нажал на кнопку Save, запись в таблице обновляется

2.2 Если пользователь нажал на кнопку Cancel, то поля вычищаются и снова отображается форма добавления

Бонусное задание: подумайте, как должно вести себя приложение, если вы при редактировании записи, нажмёте на удалить (крестик).

### Фильтрация

Предложите вариант реализации возможности фильтрации: т.е. у вас должно быть строковое поле, при введении данных в которое, будут отображаться только объекты, у которых название содержит введённую строку.

Предложите собственную реализацию данной функциональности.

Обратите внимание:

1. При пустом значении фильтра должны показываться все объекты.
2. Неважно, заполнен фильтр или нет - все функции редактирования (добавление/обновление/удаление) должны быть доступны.
Напоминаем, что фильтр - это просто текстовое поле.
