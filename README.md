Я использовал URP и Shader Graph. Для нормального отображение необходимо установить плагин Universal RP из Package Manager и в Project settings/Graphics установить Universal Render Piepline из пакета.
Так же мне не удалось сделать lightmap менее 4х мб. Выглядело слишком страшно, так что ее вес 26 мб.

Делать пока нечего было решил дублировать сцену и в одной сцене сделать lightmap поменьше. Самый максимум удалось снизить до 3мб, но использовать такой вариант или нет зависит от ракурса камеры в игре, ну а раз нужно найти золотую середину то вышло на 9мб, редактор пишет 5.3мб, но по факту 9.

Так же были проблемы с добавлением анимаций, обошел этот момент несколько стремно, блендер не мог нормально импортировать модельку, а анимации без скина воспроизводились криво, причем только на этом полицае. Хотя была бы связь с моделлером, уверен проблемы бы не было.
Вроде всё.

Вода там на крыше здания
