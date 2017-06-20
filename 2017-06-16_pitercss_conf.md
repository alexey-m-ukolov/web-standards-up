# PiterCSS Conference

## 2017-06-16, Санкт-Петербург, Россия

### Доклады
[Designing Data-Driven Products. Controlled Chaos and Evolution](#designing-data-driven-products-controlled-chaos-and-evolution), Anton Shein, Yandex  
[Paint the Web with CSS. On Creating Art with Code](#paint-the-web-with-css-on-creating-art-with-code), Eva Lettner, ChillBill  
[Creating Magic With Houdini](#creating-magic-with-houdini), Patrick Kettner, Microsoft  
[Is CSS-in-JS Really That Bad Idea?](#is-css-in-js-really-that-bad-idea), Andrey Okonetchnikov, himself  
[Chinese Typography on the Web](#chinese-typography-on-the-web), Hui Jing Chen, Wismut Labs  
[Breaking the Norm with Creative CSS](#breaking-the-norm-with-creative-css), Agnieszka Naplocha, Adobe  
[Accessible UX](#accessible-ux), Manuel Matuzovic, himself  
[Designing Declarative APIs](#designing-declarative-apis), Ilya Birman, Bureau Gorbunov  


### Открытие

Всем привет с PiterCSS, на сегодня этот твиттер зохвачен [@\_h4\_](https://twitter.com/_h4_ "Михаил Баранов") [pic.twitter.com/qxW7SRSnGZ](https://t.co/qxW7SRSnGZ)

![](https://pbs.twimg.com/media/DCbPiExUMAAV0cw.jpg)

Вот так сегодня снаружи и внутри [pic.twitter.com/RCZDgt89jj](https://t.co/RCZDgt89jj)

![](https://pbs.twimg.com/media/DCbQM4nUQAAJWaz.jpg)

![](https://pbs.twimg.com/media/DCbQMzxUMAEvTIN.jpg)

![](https://pbs.twimg.com/media/DCbQMznV0AAfG_O.jpg)

Конференция начинается. Нет, эти ребята не секция лайк-Кодина. Это секция электроник мьюзинга. [pic.twitter.com/Tv6PJoEN5T](https://t.co/Tv6PJoEN5T)

![](https://pbs.twimg.com/media/DCbX60VUQAA5mri.jpg)

Вадим [@pepelsbey\_](https://twitter.com/pepelsbey_ "Vadim Makeev") Макеев открывает [#pitercss](https://twitter.com/search?q=%23pitercss). Это первая конференция в России, посвящённая целиком CSS. А в Амстердаме сегодня [#cssday](https://twitter.com/search?q=%23cssday)

Конференция будет целиком на английском. Почему? Чтобы быть чем-то большим, чем локальное мероприятие.

Но эта трансляция будет на русском, не переживайте ;\)

Почитать трансляцию со вчерашнего [#cssday](https://twitter.com/search?q=%23cssday) \(и, возможно с сегодняшнего\) вы можете у Артура [@fliptheweb](https://twitter.com/fliptheweb "Artur Kornakov") Корнакова.

### Designing Data-Driven Products. Controlled Chaos and Evolution

Первый доклад от Антона  [@antonadrior](https://twitter.com/antonadrior "Anton Shein") Шеина. «Designing Data-Driven Products. Controlled Chaos and Evolution»

Антон работает в Яндексе, дизайнером СЕРПа.

Как лучше всего проектировать насколько сложную систему, как поисковая выдача? Все дизайнеры СЕРПа умеют верстать и программировать.

В основе — компонентный подход и БЭМ. Всё на странице — есть блок.

Чтобы не потонуть во множестве блоков и их комбинациях нужны правила их изменений.

Второй уровень борьбы с хаосом — поддержка системы компонентов. Нужно не дать ей превратиться в музей компонентов.

Дизайн-система должна подстраиваться под изменения требований к продукту. Не стоит бояться рефакторинга системы.

Если ваш дизайн живёт в графическом редакторе — рефакторинг будет болезненным. Если дизайнер работает с кодом — всё становится легко.

Если есть такая возможность — дизайнеру стоит использовать тот же стек технологий, что и разработчики. Но в Яндексе так не получается.

Все эти линтеры, контроль версий, тесты — очень сильно ограничивали дизайнеров и мешали.

Давным-давно, когда ещё не было реакта, а БЭМ был слишком многословен, дизайнеры в Яндексе познакомились с XSLT.

Это было сложно, очень сложно. Но давало возможность работать с живыми данными.

А потом ребята придумали Beast. Вот статья, про то, как пришли к нему [medium.com/@kovchiy/inter…](https://t.co/oro8e9gCwu "https://medium.com/@kovchiy/interface-components-ac2447ab5fbe"). А вот скринкаст [vimeo.com/208732806?ref=…](https://t.co/Hy2LxHncu5 "https://vimeo.com/208732806?ref=tw-share")

Так же дизайнеры поддерживают «Депо» — систему лайв-документации для блоков. С примерами и версионированием.

Депо на гитхабе — [github.com/yandex/dpt](https://t.co/TwjOHl43Rq "https://github.com/yandex/dpt")

Там не совсем хорошо с документацией, поэтому с вопросами можно обращаться напрямую к Антону.

### Paint the Web with CSS. On Creating Art with Code

Следующий доклад от Евы [@eva\_trostlos](https://twitter.com/eva_trostlos "Eva Lettner 🇷🇺") Леттнер. «Paint the Web with CSS. On Creating Art with Code». Через пару минут.

Ева живёт в Вене и работает художником-кодером в [@chill](https://twitter.com/chill "chill") ill [pic.twitter.com/qdJvVsOXmG](https://t.co/qdJvVsOXmG)

![](https://pbs.twimg.com/media/DCbnPY2UAAA-xqX.jpg)

![](https://pbs.twimg.com/media/DCbnPYqUIAETfNG.jpg)

Для многих написание кода — это магия. А потом это вдруг становится рутиной. Ева столкнулась с такой ситуацией и запустила сайд-проект.

В нём она вернулась к ощущению себя творцом. CSS-творцом.

Одно из первых css-произведений Евы — [codepen.io/eva\_trostlos/p…](https://t.co/xFoe38tPHs "https://codepen.io/eva_trostlos/pen/MeyrGP")

Но как? Ведь единственная форма, которая нам доступна в CSS — это прямоугольник.

.rectangle {  
  height: 200px;  
  height: 200px;  
  border-radius: 25px 25px 160px;   
}  
  
И вот у нас уже заготовка для лица зомби.

Старики могут вспомнить, как при помощи толстых рамок и border-color: transparent мы делали треугольники...

Вот у нас уже значительно больше форм, чем прямоугольник.

И не стоит забывать, что каждый html–элемент — это на самом деле три элементы, ведь у нас есть селекторы ::before и ::afrer.

CSS-зомби атакуе! [pic.twitter.com/sJ1cbDSP4H](https://t.co/sJ1cbDSP4H)

![](https://pbs.twimg.com/media/DCbqJsEUMAI7uIL.jpg)

Остаётся вопрос — Зачем?   
Ну а почему бы и нет?

Во-первых, это весело.  
Во-вторых, вы научитесь использовать новые технологии.  
В-третьих — присоединитесь к сообществу таких же css-творцов.

Можно ли использовать такие CSS-картинки в продакшне? Ну... На самом деле не стоит. SVG будет эффективнее.

Если это нельзя использовать в проде — бесполезно ли это? Не более бесполезно, чем любое другое хобби.

— Какой инструмент помогает тебе творить?  
— Обычный текстовый редактор. Я не пользуюсь скетчем или иллюстратором. CodePen достаточно.

— Будут ли маленькие CSS-картинки производительнее, чем маленькие png?  
— Скорее всего нет, но я точно не знаю.

Вадим поделился, что множественные box-shadow один из его любимых трюков. Если border недостаточно, он использует их. Но в разумных пределах

### Creating Magic With Houdini

Патрик [@patrickkettner](https://twitter.com/patrickkettner "Patrick Kettner") Кеттнер рассказывает про проект Гудини. «Creating Magic With Houdini»

Интерфейс первого браузера Нетскейп. CSS ещё не изобретён, но уже есть тег &lt;center&gt; [pic.twitter.com/Ne08nSLcqy](https://t.co/Ne08nSLcqy)

![](https://pbs.twimg.com/media/DCbz8EzUMAQt-Hc.jpg)

Когда CSS был-таки изобретён и встроен в IE 3, в браузеры пришёл многоуровневый процесс построения отрисовки страницы.

Этот процесс довольно медленный, и если JS что-то меняет в DOM — то процесс перезапускается с той стадии, которую затрагивает этот изменение

Перевод статьи про то, какие проблемы пытается решить проект Hoodini [habrahabr.ru/company/mailru…](https://t.co/SX4IljLfRF "https://habrahabr.ru/company/mailru/blog/282027/")

В Гудуни есть такая шткука, как Worklet. Они чем-то похожи на Workers \(работают независимо от основного потока\).

Например, можно зарегистрировать ворклет, который будет выполнять ту же работу, что делает плагин masonry, но эффективнее.

Одна из основных мыслей, которую повторяет Патрик — Гудини направлен на эффективность работы кода в браузере, а не простоту использования.

Секция вопросов:  
— Когда будет стабилизация и заморозка API?  
— Сложно сказать, возможно в течение ближайшего года.

### Is CSS-in-JS Really That Bad Idea?

В 2007 году Алексей выступал в Москве с докладом «Архитектура Фронтенда». Тогда ещё даже не было jQuery, а фронтед уже был ;\)

CSS бы разработан для добавления стилей в \*документы\*.

Однако сейчас мы чаще имеем дело с веб-приложениями, а не с отдельными документами.

При разработке приложений нам по-прежнему важно разделение ответственности, но не на уровне технологий, а на уровне компонентов.

Реакт принёс в наш мир HTML-in-JS, также известный как JSX. Кто-то считает это хорошей идеей, кто-то — ужасной.

Типичный CSS работает на глобальном уровне и ломает идею разделения ответственности на уровне компонента.

БЭМ и аналогичные методологии решают эту проблему при помощи правил именования, но сильно нагружает мозг и пальцы разработчика.

Нашлось несколько человек, которым надоело множество ручной работы и они придумали CSS-modules.

Следующий этап развития — JSS.

При использовании JSS стили живут отдельно от компонента.   
  
Styled-components размещают стили в той же области видимости, что и разметка.

Разрушение мифов.  
1. CSS-in-JS медленный.  
CSS-in-JS — это не про инлайн-стили, это про уникальность классов.

CSS-in-JS помогает получить код, который проще поддерживать и тестировать.

В Sass есть переменные и миксины.  
А в JS есть переменные и функции.

Плюсы и минусы CSS-модулей [pic.twitter.com/hfpZgtSfsm](https://t.co/hfpZgtSfsm)

![](https://pbs.twimg.com/media/DCcI4eKXsAAWCtz.jpg)

### Chinese Typography on the Web

Первый доклад после перерыва — Хуэй Джин Чэнь [@hj\_chen](https://twitter.com/hj_chen "HJ Chen"). «Chinese Typography on the Web».

Большая часть интернет-технологий придумана европейской цивилизацией, в том числе и основные строительные блоки — латинские буквы.

Однако в китайской типографике всё иначе.

Китайская система письменности значительно экономичнее. Слово «продовольственный» умещается в два иерогрфа.

Шрифты в европейской культуре делятся на две большие категории, рубленые и с засечками. Китайские иероглифы имеют четыре стиля начертания.

Каждый из типов начертания исторически имеет свою область применения.

Как указать шрифты, если вы хотите использовать китайский [pic.twitter.com/gN82oIzHLh](https://t.co/gN82oIzHLh)

![](https://pbs.twimg.com/media/DCcYHHbXgAA8b9L.jpg)

Используя свойство unicode-range в [@font](https://twitter.com/font "Font")-face можно совмещать несколько шрифтовых файлов и использовать их под одним именем в font-family.

В font feature есть специальные свойства для работы с восточной типографикой [pic.twitter.com/raDyq0CnSv](https://t.co/raDyq0CnSv)

![](https://pbs.twimg.com/media/DCcZqrZXYAAJyqD.jpg)

![](https://pbs.twimg.com/media/DCcZqrWWsAA0I_C.jpg)

Justfont  и youziku - аналоги google fonts для восточных шрифтов. [pic.twitter.com/IeLjndN4HO](https://t.co/IeLjndN4HO)

![](https://pbs.twimg.com/media/DCcadW4XgAA995h.jpg)

Спецификация CSS Writing Mode Level 3 привносит новые свойства для работы с нестандартными \(для европейцев\) способами написания текста.

Разные традиции написания текста. [pic.twitter.com/jn0g9tAHcr](https://t.co/jn0g9tAHcr)

![](https://pbs.twimg.com/media/DCcbU4SXsAASdZx.jpg)

Writhig-mode становится особенно полезен, когда дело доходит до transform: rotate\(\).

Несколько общих рекомендаций по работе с восточной типогрфикой [pic.twitter.com/dupZyT47hb](https://t.co/dupZyT47hb)

![](https://pbs.twimg.com/media/DCccEtuW0AIUYAi.jpg)

Современное состояние CSS позволяет нам добиваться большей гибкости при локализации для дальневосточной аудитории.

### Breaking the Norm with Creative CSS

Следующий доклад — Агнешка [@aganaplocha](https://twitter.com/aganaplocha "aga naplocha") Наплоха. «Breaking the Norm with Creative CSS»

Огромное число сайтов в интернете ужасающе похожи. 12-колоночная сетка и три блока — шапка, контент, подвал.

Примерно так [pic.twitter.com/2rMTbbH6Sg](https://t.co/2rMTbbH6Sg)

![](https://pbs.twimg.com/media/DCch1TIXUAANSXd.jpg)

А что в оффлайне? Откройте пару хороших печатных журналов и посмотрите — они все разные.

Агнешка выбрала несколько интересных макетов, которые она нашла в Пинтересте, и попробовала реализовать их при помощи CSS.

Гриды и clip-path — спецификации, которые позволяют делать множество вещей, стандартных для индустрии печатного глянца.

jpg + cliping path = полупрозрачный png, только в 6 раз меньше по объёму.

Ещё одна техника, позволяющая создавать интересные решения — masking. В отличие от clipping path для ограничения видимости используют растр.

Если вы использует маски и clipping со сторонних ресурсов — не забывайте про CORS. Или положите всё на один домен.

Агнешке очень понравилась форма создания бейджа на [@pitercss\_conf](https://twitter.com/pitercss_conf "pitercss_conf") ;\)

### Accessible UX

Следующий доклад — Мануэль [@mmatuzo](https://twitter.com/mmatuzo "Manuel @ pitercss") Матузович. «Accessible UX».

Мануэль начал с того, что в его фамилии на самом деле последняя буква несколько иная, но её нет на стандартной латинской клавиатуре.

К чему бы это? В мире есть много раскладок клавиатур — Querty, Quertz, а так же знакомая нам Йцукен.

Если вы хотите сделать ваш интерфейс доступным с клавиатуры — вы наверняка столкнётесь с проблемами совместимости в JS.

Мы используем event.code — и получаем проблемы распознования, какой символ нажал пользователь.

Для однозначного распознования, какую клавишу нажал пользователь — используйте event.code [developer.mozilla.org/en-US/docs/Web…](https://t.co/FFxbMoDubA "https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/code"), если возможно.

Нет никакой возможности определить, какая раскладка активна у пользователя через js api.

Тип кавычек, которые будут использоваться элементом &lt;q&gt;, зависят от значения атрибута lang у тега html.

Скринридеры также ориентируются на атрибут lang, чтобы выбрать правильный движок произношения.

А ещё его используют элементы &lt;input type='date' /&gt; и css-движок при расстановке переносов.

Псевдокласс :focus делает страницу доступной для управления с клавиатуры. А ещё есть новые селекторы :focus-ring и :focus-within.

Картинка-ответ на вопрос «кому вообще нужна навигация с клавиатуры»? [pic.twitter.com/gBo4lLMV8d](https://t.co/gBo4lLMV8d)

![](https://pbs.twimg.com/media/DCczmbjWAAI5sGc.jpg)

Семантика заголовоков \(h1 - h6\) очень важна не только для SEO, но и для скринридеров.

Атрибут "role" также используется скринридерами для упрощения навигации по странице.

— Как быть если на странице есть текст на разных языках?  
— Атрибут lang можно указывать не только для &lt;html&gt;, но и для отдельных секций.

Некоторые участники предпочитают повышенный комфорт. [pic.twitter.com/vflXzLm7Kj](https://t.co/vflXzLm7Kj)

![](https://pbs.twimg.com/media/DCc22CkXYAE-LVX.jpg)

### Designing Declarative APIs

Завершает конференцию Илья [@ilyabirmannet](https://twitter.com/ilyabirmannet "Ilya Birman") Бирман. «Designing Declarative APIs»

Императивная инициализация:   
$\('[#input](https://twitter.com/search?q=%23input)'\).superinput\(\);  
Декларативная:  
&lt;input class="superinput" /&gt;

Одна из наиболее популярных библиотек с подобным подходом — [fotorama.io](https://t.co/vylZ27pMH2 "http://fotorama.io/")

Критики говорят, что этот подход провоцирует смешение зон ответственности \(класс в html вызывает инициализацию js-кода\).

Но это делает разметку более выразительной и проще в использовании.

Если инициализация компонента требует дополнительные параметры — их можно передать как data-атрибуты.

Илья рассказывает о возможностях декларативных API на примере собственных проектов Лайкли, Эмёрдж и Жуэль [ilyabirman.ru/projects/](https://t.co/eq4Hs76rE7 "http://ilyabirman.ru/projects/")

Организаторы, докладчики и волонтеры конференции [pic.twitter.com/D4DaLRtAZt](https://t.co/D4DaLRtAZt)

![](https://pbs.twimg.com/media/DCdAv3CXcAExK6w.jpg)

Презентации и фото будут опубликованы в ближайшее время.

[#pitercss\_conf](https://twitter.com/search?q=%23pitercss_conf) завершен, спасибо, что были с нами!
