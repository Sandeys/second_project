
Форматирование текста
https://www.youtube.com/watch?v=seewcjGHreg

3:19 font-family (устанавливает семейство шрифта)
6:27 font-size (определяет размер шрифта)
7:40 font-style (определяет начертание шрифта)
8:51 font-weight (устанавливает насыщенность шрифта)
10:07 color (определяет цвет текста)
11:13 text-align (определяет горизонтальное выравнивание текста)
13:36 text-decoration (добавляет оформление текста)
14:51 text-shadow (добавляет тень к тексту)
16:30 text-transform (заглавные или прописные символы)
17:50 text-indent (отступ от левого края)
18:39 letter-spacing (определяет интервал между символами)
19:31 word-spacing (определяет интервал между словами)
20:08 white-space (управляет свойствами пробелов между словами)
21:24 line-height (устанавливает межстрочный интервал текста)
p.s. Всем удачи в начинаниях

Свойства шрифта

font-family: "Имя шрифта", "Имя шрифта", тип шрифта
Устанавливает семейство шрифта
Типы шрифта:
serif — шрифты с засечками (антиквенные), типа Times;
sans-serif — рубленные шрифты (шрифты без засечек или гротески), типичный представитель — Arial;
cursive — курсивные шрифты;
fantasy — декоративные шрифты;
monospace — моноширинные шрифты, ширина каждого символа в таком семействе одинакова (шрифт Courier).

font-size
Определяет размер шрифта элемента.

font-style:
Определяет начертание шрифта — обычное, курсивное или наклонное.
normal - Обычное начертание текста.
italic - Курсивное начертание. 
oblique - Наклонное начертание. Курсив и наклонный шрифт при всей их похожести не одно и то же. Курсив это специальный шрифт имитирующий рукописный, наклонный же образуется путем наклона обычных знаков вправо. 

font-weight:
Устанавливает насыщенность шрифта.
100 - thin
300 - lite
400 - normal
500 - medium
600 - semibold
700 - bold
900 - black


Свойства текста

color
Определяет цвет текста. Для задания цветов обычно используются числа в шестнадцатеричном коде, 
либо с помощью RGB.

text-align
Определяет горизонтальное выравнивание текста в пределах элемента. 
center - Выравнивание текста по центру.
justify - Выравнивание по ширине, что означает одновременное выравнивание по левому и правому краю. Чтобы произвести это действие браузер в этом случае добавляет пробелы между словами.
left - Выравнивание текста по левому краю. 
right - Выравнивание текста по правому краю.

text-decoration
Добавляет оформление текста в виде его подчеркивания, перечеркивания, линии над текстом и мигания. 
Одновременно можно применить более одного стиля, перечисляя значения через пробел. Это свойство наследуется и может принимать значения:
line-through - Создает перечеркнутый текст.
overline - Линия проходит над текстом.
underline - Устанавливает подчеркнутый текст. 
none - Отменяет все эффекты, в том числе и подчеркивания у ссылок, которое задано по умолчанию.

text-shadow: горизонтальное_смещение вертикальное_смещение размер цвет;
Добавляет тень к тексту.
Прмер text-shadow: 1px 1px 1px #000;

text-transform
Управляет преобразованием текста в заглавные или прописные символы.
capitalize  - Первый символ каждого слова в предложении будет заглавным. Остальные символы свой вид не меняют.
lowercase - Все символы текста становятся строчными (нижний регистр). 
uppercase - Все символы текста становятся прописными (верхний регистр).
none - Не меняет регистр символов.

text-indent
Устанавливает величину отступа первой строки блока текста. При меняется, если нам нужно создать что-то типа красной строки.

letter-spacing
Определяет интервал между символами (буквами). Используется когда нужно разрядить текст.

line-height
Устанавливает межстрочный интервал текста. Широко применяется при верстке текста.

white-space
Управляет свойствами пробелов между словами. Пименяется в основном со значением 
nowrap которое запрещает перенос строки. Таким образом весь текст отображается в одну строку и не ломается. Значение normal вернет все как было.

word-spacing
Устанавливает интервал между словами.




************************************************************************************************************


Властивості блоків. 

box-sizing
Применяется для изменения алгоритма расчета ширины и высоты элемента. 
Свойство наследуется.
content-box - Основывается на стандартах CSS, при этом свойства width и height задают ширину и высоту контента и не включают в себя значения отступов, полей и границ.
border-box - Свойства width и height включают в себя значения полей и границ, но не отступов (margin). Эта модель используется браузером Internet Exporer в режиме несовместимости.
padding-box - Свойства width и height включают в себя значения полей, но не отступов (margin) и границ (border). 
=========================================
padding
Внутренний отступ элемента
При указании поля в процентах, значение считается от ширины родителя элемента.
Свойство не наследуется.

padding: со_всех_сторон;
padding: сверху справа снизу слева;
padding: сверху_снизу справа_слева;
padding: сверху справа_слева снизу;

Отступ сверху и снизу не действует на срочные теги
=========================================
margin
Внешний отступ элемента
При указании поля в процентах, значение считается от ширины родителя элемента.
Свойство не наследуется.
Значение может быть как положительным, так и отрицательным числом.

margin: со_всех_сторон;
margin: сверху справа снизу слева;
margin: сверху_снизу справа_слева;
margin: сверху справа_слева снизу;

Отступ сверху и снизу не действует на срочные теги
=========================================
width
Устанавливает ширину блочных тегов и некоторыйх строчных (например img)
Свойство не наследуется.
width:100px;
width:10%;
=========================================
max-width
Устанавливает максимальную ширину блочных тегов и некоторыйх строчных (например img)
=========================================
min-width
Устанавливает минимальную ширину блочных тегов и некоторыйх строчных (например img)
=========================================
height:
Устанавливает высоту блочных тегов и некоторыйх строчных (например img)
Свойство не наследуется.
height:100px;
height:10%;
=========================================
min-height
Свойство не наследуется.
=========================================
max-height
Свойство не наследуется.
=========================================
overflow 
Управляет отображением содержания блочного элемента
visible - Отображается все содержание элемента, даже за пределами установленной высоты и ширины. 
hidden - Отображается только область внутри элемента, остальное будет скрыто.
scroll - Всегда добавляются полосы прокрутки.
auto - Полосы прокрутки добавляются только при необходимости.
=========================================
display:
Многоцелевое свойство, которое определяет, как элемент должен быть показан в документе.
Свойство не наследуется.

block - Элемент показывается как блочный. Применение этого значения для встроенных элементов, например тега <span>, заставляет его вести подобно блокам — происходит перенос строк в начале и в конце содержимого. 											
inline - Элемент отображается как встроенный. Использование блочных тегов, таких как <div> и <p>, автоматически создает перенос и показывает содержимое этих тегов с новой строки. Значение inline отменяет эту особенность, поэтому содержимое блочных элементов начинается с того места, где окончился предыдущий элемент. 											
inline - block - Это значение генерирует блочный элемент, который обтекается другими элементами веб-страницы подобно встроенному элементу. Фактически такой элемент по своему действию похож на встраиваемые элементы (вроде тега <img>). При этом его внутренняя часть форматируется как блочный элемент, а сам элемент — как встроенный. 											
none - Временно удаляет элемент из документа. Занимаемое им место не резервируется и веб-страница формируется так, словно элемента и не было. 
=========================================









***********************************************************************************************************



Стилізація CSS

=========================================
border
Универсальное свойство border позволяет одновременно установить толщину, 
стиль и цвет границы вокруг элемента.
border: 1px solid #000; (размер стиль цвет)
Основные стили -solid dotted dashed
=========================================
border-radius
Устанавливает радиус скругления уголков блока.
border-radius:50%; - кргуг
Можно использовать вместе с overflow: hidden;
=========================================
outline
Универсальное свойство, одновременно устанавливающее цвет, 
стиль и толщину внешней границы на всех четырех сторонах элемента. 
В отличие от линии, задаваемой через border, свойство outline 
не влияет на положение блока и его ширину. 
Также нельзя задать параметры линии на отдельных сторонах элемента, 
outline применяется сразу ко всем четырём сторонам. 
=========================================
box-shadow
Добавляет тень к элементу.
box-shadow: сдвиг_по_гориз сдвиг_по_верт радиус расстояние
Можно добавить много теней. На тень влияет свойство border-radius.
=========================================
opacity
Определяет уровень прозрачности элемента.
Отличие opacity:0; от display:none; в том что блок не убирается из верстки а только становиться прозрачным, то есть занимаемое им место остается. Так же, с прозрачными элементами все еще можно взаимодействовать, например кликать по ссылкам.
=========================================
visibility
Предназначен для отображения или скрытия элемента.
Отличие visibility: hidden; от display:none; в том что блок не убирается из верстки а только скрывается, то есть занимаемое им место остается.
Отличие visibility: hidden; от opacity:0; в том что блок скрывается и взаимодействовать с ним нельзя.
=========================================




***********************************************************************************************


background:
Универсальное свойство background позволяет установить одновременно несколько характеристик фона а именно:
=======================================================
background-color - Определяет цвет фона элемента.
=======================================================
background-image - Устанавливает фоновое изображение для элемента.

Так же значением свойства можно указать градиент:
линейный:
background:linear-gradient(to top, #fefcea, #f1da36); 
радиальный:
background:radial-gradient(ellipse at center, rgba(30,87,153,1) 0%,rgba(41,137,216,1) 50%,rgba(32,124,202,1) 51%,rgba(125,185,232,1) 100%);

Подробнее о градиентах:
http://htmlbook.ru/css3-na-primerakh/lineinyi-gradient

Инструмент создания готового кода:
https://www.colorzilla.com/gradient-editor/
=======================================================
background-position - Задает начальное положение фонового изображения, установленного с помощью свойства background-image.
=======================================================
background-repeat - Определяет, как будет повторяться фоновое изображение, установленное с помощью свойства background-image.
no-repeat -  Устанавливает одно фоновое изображение в элементе без его повторений, положение которого определяется свойством background-position (по умолчанию в левом верхнем углу). Аналогично no-repeat no-repeat.
repeat - Фоновое изображение повторяется по горизонтали и вертикали. Аналогично repeat repeat.
repeat-x - Фоновый рисунок повторяется только по горизонтали. Аналогично repeat no-repeat.
repeat-y - Фоновый рисунок повторяется только по вертикали. Аналогично no-repeat repeat.
inherit -Наследует значение родителя.
space - Изображение повторяется столько раз, чтобы полностью заполнить область; если это не удаётся, между картинками добавляется пустое пространство.
round - Изображение повторяется так, чтобы в области поместилось целое число рисунков; если это не удаётся сделать, то фоновые рисунки масштабируются.
=======================================================
background-attachment - Устанавливает, будет ли прокручиваться фоновое изображение вместе с содержимым элемента.
fixed - Делает фоновое изображение элемента неподвижным. 
scroll - Позволяет перемещаться фону вместе с содержимым.
inherit - Наследует значение родителя.
local - Фон фиксируется с учётом поведения элемента. Если элемент имеет прокрутку, то фон будет прокручиваться вместе с содержимым, но фон выходящий за рамки элемента остаётся на месте.
=======================================================
background-size  - Масштабирует фоновое изображение согласно заданным размерам.
<значение> - Задает размер в любых доступных для CSS единицах. 
<проценты> - Задает размер фоновой картинки в процентах от ширины или высоты элемента. 
auto - Если задано одновременно для ширины и высоты (auto auto), размеры фона остаются исходными; если только для одной стороны картинки (100px auto), то размер вычисляется автоматически исходя из пропорций картинки.
cover - Масштабирует изображение с сохранением пропорций так, чтобы его ширина или высота равнялась ширине или высоте блока.
contain - Масштабирует изображение с сохранением пропорций таким образом, чтобы картинка целиком поместилась внутрь блока. 
Если установлено одно значение, оно задает ширину фона, второе значение принимается за auto. Пропорции картинки при этом сохраняются. Использование двух значений через пробел задает ширину и высоту фоновой картинки.
=======================================================
Свойство background позволяет задать несколько изображений через запятую, 
причем со своими настройками позиционарования маштабирования и прокрутки



*******************************************************************************************************



Синтаксис, то есть правило записи псевдоклассов прост, мы пишем селектор класса либо селектор типа 
ставим двоеточие, пишем тот или иной псевдосласс и уже после этого открываем фигурные 
скобки и пишем нужные CSS параметры:
Селектор:Псевдокласс { параметры стиля }
================================================================================================================
Отлично, теперь рассмотрим псевдоклассы состояния.

:hover
Срабатывает при наведении на элемент, часто применяется применяется как для ссылок так и для любого другого элемента.

:active
Срабатывает при нажатии на элемент. В основном применяется к ссылкам и кнопкам.

:visited
Срабатывает для посещенных ссылок

:focus
Срабатывает при получении элементом фокуса. Часто применяется к елементам форм. Например инпутам.
================================================================================================================
Теперь рассмотрим псевдоклассы положения в коде.

:first-child
Обращение к первому элементу в блоке

:last-child
Обращение к последнему элементу в блоке

:nth-child(порядковый номер элемента)
Обращение к конкретным элементам в блоке

odd - Обращается к элементам с нечётными номерами
even - Обращается к элементам с чётными номерами
================================================================================================================



*****************************************************************************************************




Псевдоэлементы – это селекторы, которые определяют область элементов, которая изначально 
отсутствует в дереве документа. Эта область создается искусственно с помощью CSS.

Псевдоэлемент :first-line задает стиль первой строки форматированного текста. 
Длина этой строки зависит от многих факторов, таких как используемый шрифт, 
размер окна браузера, ширина блока, языка и т.д. В правилах стиля допустимо 
использовать только свойства, относящиеся к шрифту, изменению цвета текста и фона.
=================================================================================
Псевдоэлемент :first-letter определяет стиль первого символа в тексте элемента, 
к которому добавляется. 
К этому псевдоэлементу могут применяться только стилевые свойства, 
связанные со свойствами шрифта, полями, отступами, границами, цветом и фоном.
=================================================================================
Псевдоэлемент :before применяется для отображения желаемого контента до содержимого элемента, 
к которому он добавляется. Работает совместно со свойством content. 

При добавлении :before к блочному элементу, значение свойства display может быть только: block, inline, none, list-item. 
Все остальные значения будут трактоваться как block.
При добавлении :before к встроенному элементу, display ограничен значениями inline и none. 
Все остальные будут восприниматься как inline.
=================================================================================
Псевдоэлемент, который используется для вывода желаемого текста после содержимого элемента, 
к которому он добавляется. Псевдоэлемент :after работает совместно со свойством content. 

При добавлении :after к блочному элементу, значение свойства display может быть только: 
block, inline, none, list-item. Все остальные значения будут трактоваться как block.
При добавлении :after к встроенному элементу, display ограничен значениями inline и none. 
Все остальные будут восприниматься как inline.
=================================================================================
::-ms-clear {}
Задаёт стиль кнопки для очистки текстового поля. Исходно эта кнопка не видна, 
она появляется в правой части поля только при вводе текста.
Только IE
=================================================================================
::-moz-focus-inner{}
Задаёт стиль внутренней части элемента
Только FireFox
=================================================================================
« »