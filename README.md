# computer_vision_labs

Учебные лабораторные работы по компьютерному зрению

Работа 1:
– Выполните размытие изображения по Гауссу с произвольным значением . Нарисуйте изолинии для различных значений и сравните их.
– Найдите границы изображения p1 c помощью фильтра Гаусса и операторов Собеля. Сравните результаты.
– Бинаризируйте изображение p1. Вычислите количество разных объектов на нем. Воспользуйтесь функцией бинарного открытия, чтобы убрать перемычки между объектами. Вычислите центры масс для найденных объектов.
– Выполните операцию нерезкого маскирования для p1 (полутоновому и полутоновому и цветному): размойте p1, вычтите из исходного изображения размытое (полутоновому и должна увеличиться резкость)
– Сегментируйте изображение любыми двумя алгоритмами кластеризации

Работа 2: 
– Для произвольного изображения применить поворот,
растяжение и сжатие, сохранить полученные изображения.
– Построить размытое, резкое изображение с помощью
различных фильтров.
– Найти углы с помощью детектора Харриса
– Найти области SIFT
– Найти границы Canny
– Построить результаты морфологических операций

Работа 2:
– Для произвольного изображения постройте контуры
– Для любого изображения выполните сегментацию с помощью
метода водораздела, используя различные предобработки
изображения (морфологические), сравните результаты
– Для произвольного изображения протестируйте различные
алгоритмы сегментации skimage, сравните результаты
(качество и быстродействие)

Работа 4:

– Составить алгоритм определения объектов на
картинке, без использования функции matchTemplate
на основе определения контура, характеризующего
исходный объект
– Определить заданный объект на нескольких
фотографиях с помощью функции matchTemplate.
Обвести объект на фотографии в рамку.
– Найти все объекты на картинке. Сравнить результаты
работы различных методов сравнения для функции
matchTemplate. Обвести все объекты на фото рамкой.
– Для произвольного семейства (животные, растения)
протестировать 3 библиотечные обученные сети на
узнавание классов/видов животных, отметить что
распознается, что не распознается.

Работа 5:
– Найти количество шариков в видео
– Как менялось количество шариков? (сделать счетчик)
– Удалить лишние кадры заставки из видео, создать новое видео где есть горение свечи (по цветовому
диапазону)
– Взять произвольное видео с движением одного объекта и записать лог файл с перемещением
объекта по кадрам, как влияют разные алгоритмывычитания фона на распознавание Вашего
объекта?
– Склеить видео из 100 изображений, сделать распознавание классов изображений с помощью Вашей
предобученной сетки, склеить видео из размеченных кадров
– Найти на видео объект класса А с помощью match_template, склеить видео из размеченных кадров


Контрольная работа:

По видео определить является ли движущийся объект человеком
Взять видео с движущимся человеком и не человеком
Движущиеся объекты выделить прямоугольником, сохранить
прямоугольники в виде файлов jpg (crop), для каждого прямоугольника
определить класс (человек, не человек) - сетка, в лог файле написать что на
таком - то кадре был человек с кординатами x1,y1,x2,y2

