# MADE-DS-22-cv1
Для 1 ДЗ
![](score.png)

Учил локально на GTX1060 3GB. Основа бейзлайн, использовал разные сети (resnet18, resnet34, resnet50, resnext50,...)
С данными не работал, было мало времени
Основные исследования были проведены на resnet18:
провел исследование по lr от 1e-3 до 1e-4 с шагом 0.01, и 1e-3 показал на приемлимые результаты по точности и скорости
провел исследование по коэффициенту отложенной выборки, с шагом 0.05 до от 0.8 до 0.95, 0.9 показал приемлимую точность
провел исследование по числу эпох от 4 до 10, 8 показало приемлимую точность и скорость, чтобы можно было пробовать более сложные модели


