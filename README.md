# Great Book of Grudges 
В последнее время участились случаи добавления в популярные OpenSource проекты бекдоров разной степени опасности и полит агиток нацеленных на жителей России и Белоруси а также россиян и белорусов по всему миру.  
Это может нести угрозу(втч возможно и жизни)людям, а также подрывает доверие к OpenSource комьюнити и OpenSource как таковому.  
В данном проекте собираются машино и челвоеко-читаемые списки проектов содержащих такие бекдоры, и конкретных контрибьюторов за них ответственных.  
Также по мере появления будут добавляться инструкции по минимизации ущерба от таких зловредов.  
  
Также существует [альтернативный проект похожего назначения](https://docs.google.com/spreadsheets/d/1H3xPB4PgWeFcHjZ7NOPtrcya_Ua4jUolWm-7z9-jSpQ/htmlview?pru=AAABf7z88MA*ITSp0EBrKinw0LjFWZ9tzQ#gid=2074850979).  

# Содержание
[Список проектов с закладками](./projects.md) [И он же в машиночитаемом виде](./projects.json)  

# Классификация вреда наносимого закладками
Данная классификация используется втч в машиночитаемом представлении  
- MISSING - Вред отсутвует. Сюда относится печать агиток итд.
- LOW - Сабботаж работы самого проекта содержащего закладку. Сюда не относятся проекты, сабботаж работы окторых может нести угрозу жизни.
- MEDIUM - Незначительные нарушения работы хостовой системы. Fork бомбы итд.
- HIGH - Значительный вред хосту. Шифрование системы, удаление файлов, итд. Также сюда относятся проекты саботирующие свою собственную работу, но при этом критически важные, нарушение функционирования которых может нести угрозу непосредственно людям.

# Классификация по источнику закладки
- SRC - Проект содержит закладку в своем сосбвтенном коде
- DEP - Проект имеет в зависимостях другой проект с закладкой

# Классификация по актуальности
- A - на момент последнего апдейта списка закладка все еще пристусвует
- NA - на момент последнего апдейта списка закладка удалена

# Критерии по которым производятся атаки
- NONE - Срабатывает внезависимости от критериев / прсото пассивно содержит в себе что либо
- UNKNOWN - Не установленно
- IP_RU - Российский IP адрес
- IP_BY - Белорусский IP адрес
- TZ_RU - Российская временная локаль 
- TZ_BY - Белорусская временная локаль 
- KM_RU - русская арскладка клавиатуры
- POS_RU - координаты в России
- POS_BY - координаты в Белоруси
