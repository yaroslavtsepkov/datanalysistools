# Описание лабораторной работы
Лабораторная работа №3: Визуализация данных

Лекции, примеры с plotly

    Загружаем в pandas любой набор данных, в котором есть как минимум пара числовых колонок и как минимум одна категориальная с небольшим числом категорий (либо если такой датасет вам найти сложно, придётся разные датасеты для разных пунктов задания использовать)

    Matplotlib
        Построить любой график (любого рода) с помощью чистого matplotlib / pylab
        Построить несколько суб-графиков на одном графике используя .subplot.

    Графики должны быть разных типов и хотя бы два из них должны быть связаны с вашим датасетом.
    Хотя бы в одном графике подпишите оси.
    Во всех графиках подписать название графика!
    Хотя бы для одного графика одна из осей должна быть построена в логарифмическом масштабе!

    На основе Вашего датасета построить три разных вида графиков используя pandas.DataFrame.plot / Series.plot (мануал) Среди графиков должен присутствовать один boxplot (обязательно надо использовать параметр by, для исследования взаимосвязи числовой переменной и какой-либо другой).
    Графики должны быть построены как через методы DataFrame, так и через методы Series. То есть оба варианта нужно продемонстрировать.

    Seaborn
        Построить .pairplot с помощью seaborn на каком-либо наборе данных, проанализировав взаимосвязь набора числовых переменных
        Построить .jointplot, проанализировав взаимосвязь двух конкретных числовых переменных
        Построить .boxplot или .violinplot на каком-либо наборе данных, проанализировав какой-то числовой показатель в разрезе категориального
        Построить график heatmap попарной корреляции всех числовых признаков (категориальные признаки убираете из графика!)

    Построить QQ-график (и гистограмму) для одного из числовых признаков с целью проверки на соответствие его распределения нормальному распределению

    Построить любой график (связанный с вашими данными!) с помощью plotly

Прошу не копировать 1:1 мои примеры!
