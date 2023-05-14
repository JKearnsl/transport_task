## Транспортная задача с GUI

### Описание

Программа решает транспортную задачу с помощью метода потенциалов. В качестве входных данных используется 
таблица поставщиков(A), потребителей(B), а также стоимости перевозок(C). В качестве выходных данных
программа выдает базисный план перевозок, рассчитанный с помощью метода северо-западного угла, а также 
выдает оптимальный план перевозок, рассчитанный методом потенциалов и его суммарную стоимость перевозок.

Алгоритм проводит балансировку (если необходимо), а также проверяет и устраняет вырожденность.

### Интерфейс


![Screenshot_20230507_182839](https://user-images.githubusercontent.com/76239707/236687057-c34c02e9-053e-4815-80df-2882ed0c219f.png)


### Сборка

Приложение написано на `Python3.11`. Необходимо установить следующие библиотеки:

- `PyQt6`
- `prettytable`

Для запуска приложения необходимо выполнить команду `python3 main.pyw` в корневой директории проекта. 
Не забудьте добавить в `PYTHONPATH` путь к директории с Вашим проектом,
например: `export PYTHONPATH="/home/jkearnsl/Рабочий стол/project1"`.