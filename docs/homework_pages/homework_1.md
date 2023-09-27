### Домашнее Задание №1

Дедлайн: 27.10.2023

#### Моделирование распределения давления в нагнетательной скважине.

Реализовать программу по расчёту забойного давления нагнетательной скважины и построить зависимость 
забойного давления, атм от дебита закачиваемой жидкости, м3/сут (VLP).

При расчёте учитывайте, что температура меняется согласно геотермическому градиенту (нет теплопотерь).
В скважину спущена НКТ до верхних дыр перфорации, угол искривления скважины постоянный.
Солёность зависит от входной плотности.
Диапазон дебитов жидкости для генерации VLP `1 - 400 м3/сут`.

Результатом выполнения задания является *pull-request*,
содержащий в себе:
- `program.py`- файл программы
- `output.json` - результат расчёта 
Формат выходного файла доступен [по ссылке](../../homeworks/homework_1/output_example.json)
- Файлы нужно положить в папку с фамилией в директорию `homeworks/homework_1/ваша_фамилия`. 
Например, `homeworks/homework_1/uteulina`

Исходные данные нужно взять [по ссылке](https://github.com/Alina-Uteulina/course_2023/tree/main/homeworks/homework_1/input_data). 
Нужный файл = вашему номеру в списке группы.

Если непонятны сокращения, то расшифровку можно посмотреть [здесь](glossary.md).

Для реализации можно использовать [заготовку расчётного файла](../../homeworks/homework_1/demo.ipynb). 