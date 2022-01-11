![MarkDown](https://github.com/vit050587/NASA-Exoplanet-Archive/blob/master/nasa.png)
# Задание
Используя NASA Exoplanet Archive и его API, выгрузите нужную информацию по экзопланетам. Сохраните ее в виде Excel файла. На основе полученных данных постройте в Microsoft Power BI пару графиков.
## 1 часть
NASA Exoplanet Archive API
* для загрузки данных вам нужно написать скрипт на Python
* вам нужно получить по экзопланетам следующее: название планеты, название звезды (звездной системы), год открытия, метод открытия, расстояние до системы, возраст самой главной звезды (host) - всего 6 столбиков
* [здесь вводная документация](https://exoplanetarchive.ipac.caltech.edu/docs/program_interfaces.html)

* [здесь указаны все значения, которые можно получить](https://exoplanetarchive.ipac.caltech.edu/docs/API_PS_columns.html#sysdata)

* сохраните полученные данные в виде Excel таблицы в формате xlsx
*Подсказка: всего вы должны получить данные примерно по 4500 планетам*
## 2 часть
Microsoft Power BI
* требования к оформлению: придерживайтесь минимализма, все должно выглядить просто и понятно для непосвященного
* постройте первый график "количество планет по году открытия" - Например, для 2010 года - это сколько было открыто планет в 2010 году
* на первый график добавьте "количество планет с накоплением по году открытия" - Например, для 2010 года это кол-во планет, открытых с самого начала по 2010 год включительно
* добавьте к графикам фильтр по методу открытия
* разбейте звездные системы на когорты по году открытия. Постройте Матрицу, где Строки - год когорты = год открытия системы, а Стоблцы - сколько лет прошло с открытия первой планеты. А Значение - кол-во открытых планет
## Ответ
В качестве ответа нужно отправить 3 вещи: ваш Python скрипт, xlsx табличку, Microsoft Power BI файл в формате .pbix
