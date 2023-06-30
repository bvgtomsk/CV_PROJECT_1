# Проект 1 трека CV инженер курса профессия DataScinse от SkillFactory  

### Цель: Обучить модель нейронной сети распознаванию изображений лиц 5 известных IT бизнесменов
### Задачи: 
- Загрузить данные 
- Подготовить предварительную трансформацию исходных изображений для передачи в модель
- Обучить модель на обучающеф выборке
- Визуализировать результаты
- Сделать выводы по полученным результатам 

В данных соедержатся изображения 5 крупных IT бизнесмена: Илона Маска, Стива Джобса, Джефа Безоса, Марка Цукерберга и Била Гейтса.  
Необходимо построить модель верно классифицурующая изображения бизнесменов.  
В ходе работы за основу была взята предобученная модель ResNet50 с замороженными весами в сверточных слоях и змененным последним полносвязным слоям в соотетствии с необходимым колличеством классов классификации 
Обучение производилось на 3000 sampl`ах а валидации на около 920.  
Удалось получить точность на валидационной выборке 99.78 %, что является весма хорошим показателем.  

#### Структура файлов:
- cv_project_1.ipynb - ноутбук проекта
- каталог data - содержит изображения для обучения - разбит на тренировочную и валидационную часть, в каждой из которых изображения разбиты на 5 подкаталогов с менами бизнесменов, чьи изборажения содержатся в них.
- каталог test - 5 карикатурных изображений бизнесменов в качестве микротестовой выборкиц
