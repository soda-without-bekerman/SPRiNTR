![soda-logo](https://cloud.githubusercontent.com/assets/3838734/3714295/478913ee-15a0-11e4-829a-0ea6ad20f256.png)

===

###По вопросу предложений и крутых тем пожалуйста в [**ISSUE**](https://github.com/soda-io/SPRiNTR/issues)

| == ПРОБЛЕМЫ == | == РЕШЕНИЯ == |
|:-----:|:-------:|
|Качество печати|Переработать прошивку|
|Модели получаются хорошего качества не с первого раза|Учесть все недостатки печати на разных поверхностях| 
|Принтер большой по своим габаритам|Придумать хорошую конструкцию|
|Модульность|Переработать механику|
|Легкость сборки|Внедрить датчики|
|Калибровка|
|Основание|
|Механизм перемещения|
|ПО|



## == НАБЛЮДЕНИЯ ==
- Маленькие детали можно печатать на низкой скорости. Скорость регулируется джостиком на панели управления принтера. Обозначается в `%`  слева. **100%** - оптимальная скорость, на такой скорости качество моделей будет самым лучшим, **60%** - для печати маленьких моделей, **>120** - для печати круглых моделей.
- Если печатать на стекле (зеркале), то поверхность модели получается гладкой (прилегающая к стеклу)
- Черный, оранжевый, зеленый, синий - из этих цветов получаются самые качественные модели
- Качественные модели получаются при использовании клея (в ацетон кинуть кусочек пластика и очень сильно потрясти), так как при крутых поворотах экструдер не цепляет края слоя
- Зеленый отлипает от стола на t=100
- Чтобы модели не отклеивались, стол должен быть максимально грязным. То есть на него должен быть нанесен клейкий состав из ацетона и пластика. Когда состав наносится на стол, то на столе должны оставаться частички пластика. Так модель никогда не отклеится, с какой бы скоростью не двигался стол. 
- Чтобы печатать вертикально, стол должен быть жестко закреплен. Иначе калибровка сбивается. 
- Наилучшая температура экструдера для печати `225°`
- PLA пластик засоряет экструдер. 
- Если экструдер засорился, нужно протолкнуть пластик аккуратно тонкой отверткой сверху вниз (на принтере **UP** снизу вверх)


### ==Интересные решения==
****
- [Экструдер](https://www.kickstarter.com/projects/dglass3d/next-generation-3d-printer-extruders-the-rugged-hp?ref=discovery)
- [Замена ремням](http://3dprint.com/10249/corexz-3d-printer-collapsible/)
- [Принтер](https://www.kickstarter.com/projects/920076234/the-creatorbot-3d-printer-professional-grade-large?ref=category)

### ==Идеи==
****
**Внешний вид**

1. *Куб*
2. *Цилиндр*
3. *Прямоугольная площадка с выдвижным экструдером*

****

**Движение**

1. *Горизонтальное перемещение с помощью колес / подъем по оси `Z` с помощью спец. механизмов.*

2. *Во время печати неподвижно/во время подготовки движения паучка*

3. *Подвижны только ноги (ось `Z`) и экструдер (оси `X` и `Y`)*

4. *Сам принтер неподвижен. Стол двигается в плоскости, а печатная головка поднимается по оси `Z`* 

****
**Экструдер**

1. *Располагаться на вержней крышке конструкции. (чтобы избежать зацепления моделей, две противоположные стенки будут отклоняться на 90')*

2. *Неподвижен, перемежение по осям за счет ног*

3. *Двигается по осям `X~Y`*

4. *Поднимается из спец. кармана при печати / при отключении выравнивается с печатным столом*

****

**Каркас**


1. *Oсновная конструкция состоит из металических прутов и шаговых двигателей*

2. *Снаружи - пластик/внутри - металический каркас*

3. *В основном из метала. Присутствуют два ремня (только для движения стола)*
****

**Прочее**

1. *Изменение конструкции и движение стола. Хочу сделать примерно так, как на фотографии ![](http://thingiverse-production.s3.amazonaws.com/renders/7e/82/b8/b1/86/2012-04-22_18.09.12_display_large_preview_featured.jpg?raw=true)*

2. *Скрыть материнскую плату в корпус принтера и подлючить кулер для охлаждения*

3. *Добавить кулеры для всех моторов и один повесить рядом с печатной головкой для быстрого затвердевания пластика*

4. *Изменить поверхность печати. Сделать в ней отверстия, с помощью которых можно будет печать любым пластиком, в любой плоскости. Подогрев стола необязателен* 

5. *Сделать приложение для всех устройств*

6. *Внердить `Bluetooth Controler` и `Leap motion` , с помощью которых можно будет управлять принтером с помощью телефона/планшета и рук*



## == РИСКИ ==
 - снижение качества готовых моделей 
 - снижение скорости печати
 - затруднения с настройками

 
## == ЦЕЛЬ ==

- Собрать новый 3D принтер

## == ЗАДАЧИ ==

- Уменьшить вес 
- Облегчить доступ              
- Упростить управление
- Внедрить датчики, сенсоры                
- Увеличить размер печатного стола         

## == ДОРОЖНАЯ КАРТА ==

| Tm     | Состояние |  Список дел                               |
|:-------|:---------:|-------------------------------------------|
| 3.04   | **✓**     | Поиск запчастей                           | 
| 10.04  | **✓**     | Переработка 3D моделей (часть запчастей)  |
| --.--  | **▢**     | Примерное представление принтера          |       
| --.--  | **▢**     | Сборка принтера                           |        


## == КОНКУРЕНТЫ ==
- [MakerBot Replicator 2](http://www.makerbot.com)
- [Peachy Printer](http://www.peachyprinter.com)
- [ProtoBlast](http://sfera-3d.ru/products/3d-printer-protoblast)
- [PrintBox3D One](http://sfera-3d.ru/products/3d-printer-printbox3d-one)
- [Picaso 3D Builder](http://sfera-3d.ru/products/3d-printer-picaso-3d-builder)
- [UP! mini](http://www.pp3dp.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=6&category_id=1&option=com_virtuemart&Itemid=37)

### == Литература ==
****
- **Менторы**
- [Thingiverse](http://www.thingiverse.com/)
- [Kickstarter](https://www.kickstarter.com/)
- [Google](https://google.com)
- [Roboforum](http://roboforum.ru/)
- [Marlin](http://reprap.org/wiki/Marlin/ru)
- [Калибровка принтера](http://roboforum.ru/forum107/topic12700.html)
- [Popular mechanics](http://www.popmech.ru/gadgets)
- [3DCorp](http://3dcorp.ru/)
- [SLS](http://can-touch.ru/blog/sls/)
- [Технологии печати](http://www.orgprint.com/ru/wiki/obzor-tehnologij-3D-pechati)


## == СОАВТОРЫ ==

### {У}

| Паша | Максим |  Шероз  |  Лёня  |
|----|----|----|----|
|[![PavelShalaginov](https://avatars0.githubusercontent.com/u/3833771?s=74)](https://github.com/PavelShalaginov) | [![MaximLoguncov](https://avatars2.githubusercontent.com/u/3838734?s=74)](https://github.com/MaximLoguncov)|[![SherozKarimov](https://avatars0.githubusercontent.com/u/4226210?s=74)](https://github.com/SherozKarimov)|[![LeonidProkopovich](https://avatars2.githubusercontent.com/u/6639503?s=74)](https://github.com/leonidprokopovich)|


### {M}

| Кирилл |  Виталий  | 
|----|----|
|![Kirill Temnov](https://avatars1.githubusercontent.com/u/147170?s=74)|![Vitaly GB](https://avatars0.githubusercontent.com/u/842476?s=74)

====


****

#==Авторские права==
**Copyright (c) 2014 SODA LABS. The MIT License (MIT).**
![](https://cloud.githubusercontent.com/assets/3838734/4271150/c9449722-3cd4-11e4-8655-72ffe56c7dbf.png)

