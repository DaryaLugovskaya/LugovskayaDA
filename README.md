# LugovskayaDA
**Для выполненных заданий** 
1. **Презентация к докладу** по статье Jan Rybicki, David Hoover, Mike Kestemont *"Conrad, Ford and Rolling Delta"*. Способ определения авторства текстов интересен, но для моей научной работы не подошел: как оказалось, в интересующих меня материалах (например, полосах газеты "Возрождение" 1925-1940) намного меньше 10 тыс. слов. 
2. **Черновик стихотворений А. С. Пушкина "Цветок" и "Поэт и толпа"** 1828 год, выгруженный из *Текстографа*.
3. **Корпусное исследование**, для которого выбраны несколько стихотворений В. Ф. Ходасевича, помещенные в повесть "Жизнь Василия Травникова". Нам показалось интересным посмотреть по Корпусу, что современники Ходасевича моглиувидеть общего между поэзией Травникова (то, что неизвестный автор рубежа XVIII - XIX веков - литературная мистификация, современники автора поняли не сразу).  Ходасевич включает в книгу одно полное стихотворение и несколько отрывков - для пятистраничного анализа мы и выбрали это законченное стихотворение.
4. **Построение сети персонажей** *комедии А. А. Шаховского "Урок кокеткам, или липецкие воды"*. В "Списке действующих лиц" названы 11 персонажей, но дважды на сцене появлеются "Слуги" или "Слуга" - реплик они не произносят, поэтому в сеть не были включены. Ребра в графе протянуты в том случае, если герой появляется в явлении, т.е. участвует в диалоге. 
*Два кластера* обозначены, соответственно, оранжевым и зеленым. *Оранжевые"*- круг семьи Холмских, *зеленые"*- те, кто принимает участие в организации праздника, графиня Лелева, ее почитатель, барон Вольмар (Пронский, как оказалось, не относится к ним - он помещен в другой кластер, и это деление отражает финал комедии).
**Статистика по графу:**
*12 узлов*
Показатель *betweenness* невысок: 0 - 0,25 - сложной разветвленной сети нет, практически все персонажи так или иначе взаимодействуют, в некоторых явлениях появляются все действующие лица.
*Closeness centrality*: наиболее удалены от центра сети Оленька, Семен и Фиалкин. Если два последних второстепенных персонажа появляются в пьесе заметно реже, то Оленька более важна для сюжета (но за неё действует служанка Саша, одно из наиболее активных лиц). Соответственно Eccentricity для этих героев максимально - они дальше всех стоят от других персонажей
*Центральные узлы* - Барон Вольмар, Угаров, Саша, Графиня Лелева, граф Ольгин, князь Холмский, княжна Холмская, Пронский.
*Max вес ребра* =16  графиня Лелева - Саша (наиболее активные персонажи, между которыми происхожит постоянная слоесная перепалка).
*Средняя длина пути*=1,036
