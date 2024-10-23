# senla_kurs_task
## Автор

- **Максим Бырсан** 

# Проект Симуляции Экосистемы

## Описание проекта

Данный проект представляет собой симуляцию экосистемы, в которой различные типы организмов взаимодействуют на основе определённых правил поведения. Экосистема состоит из **Хищников**, **Травоядных**, **Растений** и **Редуцентов**, и функционирует в моделируемой среде с изменяющимися **условиями мира** (такими как температура, влажность и доступная вода).

Цель симуляции — наблюдать, как виды взаимодействуют, выживают и развиваются с течением времени. Симуляция основана на поведениях, таких как питание, размножение и смерть, под влиянием внешних факторов.

### Возможности

- **Симуляция взаимодействий видов**: Организмы реагируют на изменяющиеся условия окружающей среды.
- **Разнообразная экосистема**: Включает Хищников, Травоядных, Растения и Редуцентов.
- **Динамичные условия мира**: Экологические факторы, такие как температура, вода и влажность можно изменять
- **Механика выживания**: Каждый вид имеет свои шансы на выживание, зависящие от наличия пищи и условий среды. Пищей у нас являются другие виды, травоядные едят растения, хищники едят травоядных, хищников кушают редуценты и редуценты потребляются растениями, если какой-то элемент пищевой цепи вымрет, то вымрут все остальные, а такое рано или поздно происходит, если условия не идеальные для всех. Коэффициенты выживаемости не дают 100% гарантии того, что кто-то останется последним.
- **Поведение существ**: Виды могут размножаться, умирать или питаться в зависимости от своей категории.

### Запуск
Запустите симуляцию с помощью ecosystem.bat

### Взаимодействуйте с симуляцией через консоль. Доступные команды:
start — Запустить симуляцию.
stop — Остановить симуляцию.
add — Добавить новое существо в экосистему.
change — Изменить условия мира.
display — Показать текущие условия и популяцию.
save — Сохранить текущее состояние мира.
load — Загрузить состояние мира из файла.
exit — Выйти из программы.

Импорт и экспорт симуляции должен быть формата
F:\....\dataexample.txt

Вывод действий приложения происходит в файл simulation.txt

### Формат оформления стартовых данных симуляции
//Порядок соблюдать обязательно
//Год 
100
//Температура
25
//Вода
125
//Влажность
70
//Вид, название, популяция, комфортная температура, комфортное количество воды, комфортная влажность
HERBIVORE, DEER, 1000, 15, 100, 70
HERBIVORE, RABBIT, 1000, 20, 50, 80
HERBIVORE, GIRAFFE, 1000, 25, 200, 60
PREDATOR, LION, 1000, 30, 150, 50
PREDATOR, WOLF, 1000, 30, 150, 50
PREDATOR, TIGER, 1000, 30, 150, 50
PLANT, GRASS, 10000, 0, 200, 0
DECOMPOSER, BACTERIA, 1000, 20, 50, 80




