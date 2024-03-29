
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






**************************************************************************************************




Свойство position
Устанавливает способ позиционирования элемента относительно окна браузера или других объектов 
на веб-странице. Вспомогательные свойства left, right, top и bottom управляют положением элемента, 
а z-index управляет наложением друг на друга по оси Z.

Значения:
static - элемент позиционируется относительно родителя и соседних элементов
relative - элемент позиционируется как static но можно двигать его относительно своего положения
absolute - элемент позиционируется относительно ближайшего родителя с relative, absolute, fixed и sticky
fixed - элемент позиционируется относительно окна браузера
sticky - элемент позиционируется как static но когда верхняя граница элемента будет 
находиться на расстоянии, указанном в параметре top, от верхней границы окна браузера (либо указанном в параметре bottom от нижней), 
он останется в этом положении относительно окна до тех пор пока его нижняя граница 
не упрется в другой sticky элемент или конец родительского элемента
inherit - берет значение от родителя
==========================================================
Свойства:
top, bottom, left и right - управляют положением элемента сверху снизу слева и справа.
Значения могут указываются в том числе в процентах и могут иметь отрицательные значения.
Работают с элементами к которым применен один из параметров 
position:relative,position:absolute,position:fixed и position:sticky (только top или bottom)
==========================================================
Свойство: z-index
Управляет наложением друг на друга элементов с
параметрами position:relative,position:absolute,position:fixed по оси Z



*******************************************************************************************************



ШПАРГАЛКА
========================================================================
Каталог шрифтов:
https://nomail.com.ua/
Google Fonts:
https://fonts.google.com/
Конвертер шрифтов:
http://www.font2web.com/
========================================================================
@font-face {
	font-family: 'Имя шрифта';
	font-display: swap;
	src: url("../fonts/файл шрифта.eot");
	src: local("O"), url("../fonts/файл шрифта.woff") format("woff"), 
			url("../fonts/файл шрифта.ttf") format("truetype"), 
			url("../fonts/файл шрифта.svg") format("svg");
	font-weight: normal;
	font-style: normal;
}
========================================================================
font-family: "Имя шрифта", "Имя шрифта", тип шрифта
Устанавливает семейство шрифта
Типы шрифта:
serif — шрифты с засечками (антиквенные), типа Times;
sans-serif — рубленные шрифты (шрифты без засечек или гротески), типичный представитель — Arial;
cursive — курсивные шрифты;
fantasy — декоративные шрифты;
monospace — моноширинные шрифты, ширина каждого символа в таком семействе одинакова (шрифт Courier).
========================================================================
font-weight:
Устанавливает насыщенность шрифта.
100 - thin
200 - UltraLite
300 - lite
400 - normal
500 - medium
600 - semibold
700 - bold
800 - Heavy
900 - black
========================================================================



****************************************************************************************************




=================================================
Блок – это функционально независимый компонент страницы, который может быть повторно использован. Когда мы задаем блоку имя класса то должны отвечать на вопрос «что это?» а не «какой, как выглядит?».
=================================================
Элемент – это составная часть блока, которая не может использоваться в отрыве от него. Так же как для блока имя класса должно отвечать на вопрос «Что это?», но синтаксис записи будет следующим:
имякласса__имяэлемента
=================================================
Модификатор.
Применяется для определения или уточнения внешнего вида, состояния или поведения блока либо элемента. Когда нужно выделить некий объект из множества таких же.
Имя класса модификатора должно отвечать на вопрос «какой?» «как выглядит?» «как себя ведет\состояние?»
Модификатор дописывается к классу блока либо элемента путем дублирования основного класса с добавлением одного нижнего подчеркивания и имени модификатора.
===================Вложенность блоков==============================
<!-- Блок `about` -->
<div class="about">
	<!-- Вложенный блок `title` -->
	<div class="title"></div>
	<!-- Вложенный блок `subtitle` -->
	<div class="subtitle"></div>
</div>
===================Вложенность элементов==============================
<!-- Верно -->
<!-- Блок `row` -->
<div class="row">
	<!-- Элемент `column` -->
	<div class="row__column ">
		<!-- Элемент `item` -->
		<div class="row__item">

		</div>
	</div>
</div>

<!-- Неверно -->
<!-- Блок `row` -->
<div class="row">
	<!-- Элемент `column` -->
	<div class="row__column ">
		<!-- Элемент `item` -->
		<div class="row__column__item">

		</div>
	</div>
</div>
====================Принадлежность элементов===================================
<!-- Верный пример -->
<!-- Блок `about` -->
<div class=" about">
	<!-- Элемент `title` -->
	<div class="about__title"></div>
	<!-- Элемент `subtitle` -->
	<div class=" about__subtitle"></div>
</div>


<!-- Неверный пример -->
<!-- Блок `about` -->
<div class=" about">
	<!-- Элемент `title` -->
	<div class="about__title"></div>
</div>
<!-- Элемент `subtitle` -->
<div class=" about__subtitle"></div>

====================Необязательность элементов===================================
<!-- Блок `about` -->
<div class=" about">
	<!-- Вложенный блок `title` -->
	<div class="title"></div>
	<!-- Вложенный блок `subtitle` -->
	<div class="subtitle"></div>
</div>
====================Модификатор===================================
<nav class="menu">
	<a href="" class="menu__item menu__item_active">HOME</a>
	<a href="" class="menu__item">ABOUT US</a>
	<a href="" class="menu__item">PORTFOLIO</a>
	<a href="" class="menu__item">CONTACT</a>
</nav>
====================Микс===================================
<!-- Блок `about` -->
<div class=" about">
	<!-- Элемент `title` -->
	<div class="about__title title"></div>
	<!-- Элемент `subtitle` -->
	<div class=" about__subtitle subtitle"></div>
</div>

=======================================================================================================




****************************************************************************************************

МЕТА теги

Основные теги влияющие на отображение страницы

<!-- Кодировка страницы -->
<meta http-equiv="Content-type" content="text/html;charset=UTF-8">
С появлением HTML5 можно использовать 
<meta charset="UTF-8">
<!-- Настройки адаптивности страницы  -->
Фиксированная ширина
<meta name="viewport" content="width=1170">
Адаптивность
<meta name="viewport" content="width=device-width">

<!-- Отключает принудительную ссылку у номера телефона на iOS -->
<meta name="format-detection" content="telephone=no">

=================================================

SEO

<!-- Краткое описание страницы  -->
<meta name="description" content=" ">
Пишем не более 140 символов.
<!-- Ключевые слова страницы  -->
<meta name="keywords" content=" "> 
Пишем не более 20ти слов. Ключевые фразы разделяем запятой.

<!-- Управление доступом поисковых роботов к странице -->
<meta name="robots" content="">

По умолчанию страница индексируется поисковыми система, то есть этот мета тег дополнительно указывать не нужно. Но если задача стоит запретить либо ограничить индексацию, то существуют следующие значения:

none – запретить индексацию страницы полностью.
noindex – запретить индексацию содержимого страницы.
nofollow – игнорировать ссылки в пределах веб-страницы. 
noimageindex - запретить индексацию присутствующих на странице изображений
noarchive - запретить  вывод в результатах поиска ссылки «Сохраненная копия»
nosnippet - запретить  вывод в поисковой выдаче под названием страницы фрагмента текста, описывающего её содержание.

Значения указываются через запятую. Например:

Запрет индексации страницы полностью будет выглядеть так:
<meta name="robots" content="noindex, nofollow">
или так
<meta name="robots" content="none">

Запрет индексации ссылок и изображений на странице будет выглядеть так:
<meta name="robots" content="noimageindex, nofollow">
при этом текст страницы будет доступен к индексации.

=================================================
Технические
<!-- Автор страницы -->
<meta name="Author" content="Пупкин Василий Петрович"> 
<!-- Авторские права -->
<meta name="Copyright" content="Зимина Татьяна Юрьевна"> 
<!-- Адрес автора -->
<meta name="Address" content="Луна, кратер №97">
<!-- Редирект (перезагрузка) страницы. Задержка в секундах; url=Адрес сайта/страницы -->
<meta http-equiv="refresh" content="S; url=URL">

S= Задержка в секундах
URL= Адрес сайта/страницы

=================================================

Для социальных сетей
 
Facebook
Что бы настроить вид нашей страницы в посте мы пишем следующие мета теги:

<!-- локализация сайта, для русскоязычного сайта ru_RU -->
<meta property="og:locale" content="ru_RU">
<!-- тип контента, по умолчанию используется article -->
<meta property="og:type" content="article">
<!-- заголовок страницы, который будет выводится в записи социальной сети -->
<meta property="og:title" content="META теги">
<!-- описание страницы -->
<meta property="og:description" content="Описание страницы про META теги">
<!-- ссылка на изображение, которое будет публиковаться в записи -->
<meta property="og:image" content="http://fls.guru/meta/img/bg.jpg">
<!-- ссылка на текущую страницу -->
<meta property="og:url" content="http://fls.guru/meta/ ">
<!-- название сайта -->
<meta property="og:site_name" content="Фрилансер по жизни">

Проверить разметку можно в валидаторе от Facebook https://developers.facebook.com/tools/debug/sharing/


Подробнее о протоколе Open Graph можно почитать в официальной документации по ссылке в описании. https://ruogp.me/

Для создания Twitter Cards мета теги будут иметь другой вид:

<!-- Тип карты, по умолчанию используется summary -->
<meta name="twitter:card" content="summary">
<!-- Имя/логин автора -->
<meta name="twitter:site" content="Жека">
<!-- Название страницы -->
<meta name="twitter:title" content="META теги">
<!-- Описание страницы -->
<meta name="twitter:description" content="про META теги">
<!-- Cсылка на изображение -->
<meta name="twitter:image" content="http://fls.guru/meta/img/bg.jpg">

Проверяем результат в валидаторе твиттер 
https://cards-dev.twitter.com/validator

Подробнее о создании Twitter Cards можно почитать в официальной документации по ссылке в описании.
https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started






*****************Адаптивная верстка****************************

Адаптивная верстка

Условия медиазапросов (@media)

Тип устройства:
all 	Подходит для всех типов устройств.
print 	Предназначен для страничных материалов и документов, просматриваемых на экране в режиме предварительного просмотра печати.
screen 	Предназначен в первую очередь для экранов цветных компьютерных мониторов.
speech 	Предназначен для синтезаторов речи.

Характеристики устройства:
width 	
Проверяет ширину области просмотра. Значения задаются в единицах длины, px, em и т.д., например, (width: 800px). Обычно для проверки используются минимальные и максимальные значения ширины.
min-width 
применяет правило если ширина области просмотра больше значения, указанного в запросе, max-width — ширина области просмотра меньше значения, указанного в запросе.
height 	
Проверяет высоту области просмотра. Значения задаются в единицах длины, px, em и т.д., например, (height: 500px). Обычно для проверки используются минимальные и максимальные значения высоты.
min-height 
применяет правило если высота области просмотра больше значения, указанного в запросе, max-height — высота области просмотра которого меньше значения, указанного в запросе.
aspect-ratio 	
Проверяет соотношение ширины к высоте области просмотра. Широкоэкранный дисплей с соотношением сторон 16:9 может быть помечен как (aspect-ratio: 16/9).
min-aspect-ratio 
проверяет минимальное соотношение, max-aspect-ratio — максимальное соотношение ширины к высоте области просмотра.
orientation 	
Проверяет ориентацию области просмотра. Принимает два значения: (orientation: portrait) и (orientation: landscape).
resolution 	
Проверяет разрешение экрана (количество пикселей). Значения также могут проверять количество точек на дюйм (dpi) или количество точек на сантиметр (dpcm), например, (resolution: 300dpi).
min-resolution 
проверяет минимальное разрешение экрана, max-resolution — максимальное.
color 	
Проверяет количество бит на каждый из цветовых компонентов устройства вывода. Например, (min-color: 4) означает, что экран конкретного устройства должен иметь 4-битную глубину цвета.
min-color 
проверяет минимальное количество бит, max-color — максимальное количество бит.
color-index 	
Проверяет количество записей в таблице подстановки цветов. В качестве значения указывается положительное число, например, (color-index: 256).
min-color-index 
проверяет минимальное количество записей, max-color-index — максимальное количество записей.
monochrome 	
Проверяет количество битов на пиксель монохромного устройства. Значение задается целым положительным числом, например, (min-monochrome: 8).
min-monochrome 
проверяет минимальное количество битов, max-monochrome — максимальное количество битов.
-webkit-device-pixel-ratio 	
Задаёт количество физических пикселей устройства на каждый CSS-пиксель.




***************************************************************






Всю компьютерную графику можно разделить на две большие части – это растровая и векторная графика. Так же существую несколько видов графики на сайте.
Первый вид - иконки. Как правило - это небольшие простые контурные картинки, которые всячески улучшают восприятие информации. Ими могут сопровождаться текстовые надписи и заголовки, а также элементы управления и навигации. Тут идеально подойдет как раз векторный формат графики. 
Второй вид - это фоновые изображения и элементы дизайна веб - приложения. Они могут быть частично прозрачными и даже содержать анимацию. Тут в основном используется растровый формат графика и иногда векторный.
Ну и третий вид - это непосредственно изображения контентной части сайта, то есть картинки которые находятся в статьях, различных фото галереях слайдерах и так далее. Тут у нас только растровые изображения.
Первый и наверное самый известный это формат JPEG/JPG (Joint Photographic Experts Group). 
Следующий формат PNG (Portable network graphics) – это тоже растровый формат, но у него есть супер способность – отдельные его части могут быть прозрачными. 
Наконец то мы добрались и до векторного формата - это SVG (Scalable Vector Graphics).  Ну а сейчас нам достаточно знать файл в таком формате отлично подойдет для иконок нашего сайта. 
А мы движемся вперед и сейчас я хочу тебя познакомить с форматом который приходит на замену всем растровым форматам о которых мы говорили ранее. На самом деле их есть несколько это и  JPEG 2000 и JPEG XR но самый крутой это WebP!
.ico (favicon.ico) поддерживает прозрачность и используется для указания графической иконки нашего сайта во вкладке браузера. А так же для отображения иконки веб приложений. 

КАРТИНКИ та форматування

Свойство object-fit
Свойство object-fit определяет, 
каким образом содержимое замещаемых элементов будет подогнано к краям контейнера 
тега в случае, когда для элемента заданы ширина и высота, отличные от его собственных размеров. 



fill
Значение по умолчанию. Содержимое замещаемого элемента полностью заполняет область контейнера тега, используя его высоту и ширину.
contain
Содержимое элемента масштабируется, выравниваясь по центру с сохранением пропорций таким образом, чтобы полностью поместиться внутри контейнера.
cover
Содержимое элемента обрезается, выравниваясь по центру с сохранением пропорций таким образом, чтобы полностью заполнить область контейнера.
scale-down
Содержимое элемента выбирает из двух значений none и contain то значение, которое даёт меньшие размеры.
none
Замещаемое содержимое не изменяет свои собственные размеры, чтобы поместиться и заполнить область контейнера.
initial
Устанавливает это свойство в значение по умолчанию.
inherit
Наследует значение свойства от родительского элемента.

============================================================================

Свойство object-position
Свойство object-position используется в сочетании с object-fit и задаёт положение содержимого замещаемого элемента внутри контейнера 
относительно координатных осей X и Y. Значение по умолчанию 50% 50%. 

============================================================================

HTML-элемент <picture> служит контейнером для одного или более элементов <source> и одного элемента 
<img> для обеспечения оптимальной версии изображения для различных размеров экрана. 
Браузер рассмотрит каждый из дочерних элементов  <source> и выберет один, соответствующий лучшему совпадению; е
сли совпадений среди элементов <source> найдено не будет, то будет выбран файл, указанный  атрибутом  src элемента <img> . 
Затем выбранное изображение отображается в пространстве, занятом элементом <img>. 
==============================================================================
Абсолютная единица - не зависит от значений других свойств. Ее можно назвать еще фиксированной или окончательной.
Относительная единица - зависит от того или иного значения других свойств.

EM – относительная единица, размер формируется относительно размера шрифта (font-size) родителя. Как мы знаем, свойство размера шрифта font-size наследуется потомками. Поэтому, указывая тот или иной размер в EM нужно четко понимать какой размер шрифта влияет на данный элемент. Как и пиксели, значение EM можно указывать дробные.
REM - относительная единица, размер формируется относительно размера шрифта (font-size) в теге html или браузера по умолчанию.

============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================


                        КОРИСНІ ПОСИЛАННЯ 
BACKGROUND      https://fls.guru/cssbackground.html
POSITION        https://fls.guru/cssposition.html
FLEX-BOX		http://fls.guru/flexbox.html
TRANSITION		https://fls.guru/csstransition.html
ANIMATION		https://fls.guru/cssanimation.html
TRANSFORMATION	https://fls.guru/transform.html
GRID 			https://fls.guru/grid.html
Одиниці виміру	https://fls.guru/css-units.html

                        ШРИВТ
Google Fonts: https://fonts.google.com/
Каталог шрифтов: https://nomail.com.ua/
Конвертер шрифтов: http://www.font2web.com/

                        Сайт препроцессора SASS
https://sass-scss.ru/guide/

						ЗОБРАЖЕННЯ 
👉 Метод "IBG" - https://fls.guru/ibg.html
👉 Онлайн декодер WebP - https://squoosh.app/
👉 Сервис создания favicon - https://www.favicon.by/

