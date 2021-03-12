# DataScience_PythonLibrary
DataScience_PythonLibrary courses GeekBrains

Задание:
#### Используя данные из обучающего датасета (train.csv), построить модель для предсказания цен на недвижимость (квартиры). С помощью полученной модели, предсказать цены для квартир из тестового датасета (test.csv).

Целевая переменная:
*Price*

Метрика качества:
R2 - коэффициент детерминации (sklearn.metrics.r2_score)  
<center><a href="https://www.codecogs.com/eqnedit.php?latex=R^2=1-\frac{\sigma^2}{\sigma_y^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?R^2=1-\frac{\sigma^2}{\sigma_y^2}" title="R^2=1-\frac{\sigma^2}{\sigma_y^2}" /></a>

Описание датасета:
Id - идентификационный номер квартиры

DistrictId - идентификационный номер района

Rooms - количество комнат

Square - площадь

LifeSquare - жилая площадь

KitchenSquare - площадь кухни

Floor - этаж

HouseFloor - количество этажей в доме

HouseYear - год постройки дома

Ecology_1, Ecology_2, Ecology_3 - экологические показатели местности

Social_1, Social_2, Social_3 - социальные показатели местности

Healthcare_1, Helthcare_2 - показатели местности, связанные с охраной здоровья

Shops_1, Shops_2 - показатели, связанные с наличием магазинов, торговых центров

Price - цена квартиры
