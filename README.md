# web_seminar_JSON_XML
Задача: JSON и XML
Задача 1: проверить XML на Well formed:

    <surname>Иванов</surname>

    <name>Иван</name>

    <patronymic>Иванович</patronymic>

    <birthdate>01.01.1990</birthdate>

    <birthplace>Москва</birthplace>

    <phone>8 926 766 48 48</phone>
</req>
Ответ: Выполнено. Все верно!.

Задача 2: проверить JSON на Well formed:

{

    ""surname"": ""Иванов""

    ""name"": ""Иван""

    ""patronymic"": ""Иванович""

    ""birthdate"": ""01.01.1990""

    ""birthplace"": ""Москва""

    ""phone"": ""8 926 766 48 48""
}

Ответ: Выполнено. Неправильно, исправил. Коллекция должна быть заключена в [] - скобки, а объекты в ней в {} - скобки. Нужно убрать парные ковычки и поставить запятые в конце каждой строки.
.
