# 2021-graphics-rt

# Лабораторная работа 1. Трассировка лучей.

## Цель работы

* Знакомство с основными принципами трассировки лучей: базовым алгоритмом и вариантами реализации
* Создание и отрисовка 3D-сцены на основе предложенного шаблона

## Требования к работе

Необходимо расширить предложенный шаблон проекта на языке С++, дополняя его следующим:

* Базовый алгоритм трассировки в зависимости от варианта:
* дописать генерацию луча, выходящего из камеры
** четные номера списка: рекурсивная трассировка
** нечетные номера списка: алгоритм Уиттеда
* Добавить геометрические объекты и соответствующие их отрисовку:
** сфера
** прямоугольный параллелепипед
** треугольник
** квадрат
* Материалы объектов:
** диффузный
** идеальное зеркало
* Освещение:
** фоновое (ambience)
** четные номера списка: прямое освещение
** нечетные номера: точечное освещение (минимум один светящийся объект)

Результатом выполненной работы является представленный проект и изображение-сцена.
