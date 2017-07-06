HTML (ing. Hypertext Markup Language) — brauzerin oxuya biləcəyi hər hansı sənədi və ya səhifəni yaratmaq üçün xüsusi hipermətn dilidir. HTML internetin fundamental baza texnologiyasıdır və veb-səhifənin növünü, funksiyasını təyin edən diskriptorlar əsasında yaradılmış dildir.
HTML dilinin inkişaf tarixi 1989-cu ildə Oksford Universitetinin tələbəsi Tim Berners-Li tərəfindən hipermətnli sənəd sisteminin çıxarılması təklifi ilə başladı. 
## Onun mövcud olan versiyaları aşağıdakılardır:
1) HTML 0.9;
2) HTML 2.0 — 22 sentyabr 1995-ci il;
3) HTML 3.2 — 14 yanvar 1997-ci il;
4) HTML 4.0 — 18 dekabr 1997-ci il;
5) HTML 4.01 (upgrade olunmuş) — 24 dekabr 1999-ci il;
6) HTML 4.01 Strict əsasında olan ISO/IEC 15445:2000 — 15 may 2000-ci il;
7) HTML5 — 28 oktyabr 2014-ci il;
8) HTML 5.1 - dekabr 2012 ildə qurulmağa başladı. 2016 noyabrın 1-indən istifadəyə yararlıdır.

Rəsmi HTML 1.0 spesifikasitası mövcud deyil. 
1995-ci ilə qədər bir çox qeyri-rəsmi HTML standartları var idi. 
Standart versiyanı onlardan fərqləndirmək üçün ona dərhal 2 nömrəsi verildi.

3-cü versiya ümümdünya torun Konsorsiyumu tərəfindən irəli sürülmüş təklif əsasında (W3C) 1995-ci il mart ayında yaradıldı və müxtəlif yeni imkanları özü ilə gətirdi. Buna misal olaraq cədvəllərin yaradılması, çətin riyazi formulların göstərilməsi, gif formatının dəstəklənməsi və s. 
Baxmayaraq ki bu standart əvvəlki ilə uyuşurdu onun realizasiyası o vaxtın brauzerləri üçün çətin idi.
3.1 versiyasl rəsmi olaraq heç vaxt yayımanmayıb və növbəti standart versiya HTML 3.2 sayılıb. hansında ki 3.0 versiyasının bəzi xüsusiyyətləri buraxılmışdır, lakin Netscape Navigator və Mosaic brauzerləri üçün qeyri-standart yeni elementlər daxil edilmişdir.

HTML 4.0 standart təmizlənməsi aparıldı. 
Bu versiyada çox elementlər yararsız və məsləhət görülməyən qəbul edilmişdir (deprecated). 
Xüsusilə şriftin xüsusiyyətlərini dəyişmək üçün istifadə olunan <font> teqi, köhnəlmiş kimi qəbul edildi (onun yerinə CSS-in stillər cədvəlindən istifadə etmək nəzərdə tutulurdu).

1998-ci ildə ümümdünya konsorsiyum toru HTML 4 əsasında olan lakin XHTML sintaksisinə uyğun gələn yeni hypertext dili üzərində işləməyə başladı. 
Nəticədə yeni dilin adı XHTML oldu. 
26 yanvar 2000-ci ildə I veresiya XHTML 1.0 ümümdünya konsorsiyum toru tərəfindən recomend səviyyəsində qəbul olundu.

# HTML5-dƏ HTML 4-dən fərqli olaraq nələr yarandı?
- HTML5-də yeni doctype yarandı, hansını ki yadda saxlamaq daha rahatdır.

İndi o belə yazılır:

<!DOCTYPE HTML>
Onun yazıldığı reqistr da önəm daşımır onu hətta belə də yazmaq olar:

<!doctype HTML>
və belə

<!doctype html>
Bu qısa yazılış əvvəlki uzun yazılışı əvəz edir:

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">

- İndi kodirovjkanı yeni qısaldılmış yolla göstərmək olar:

<meta charset="UTF-8">
Köhnə versiyadakından fərqli olaraq:

<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

- Səhifənin məntiqinə və semanticasına yeni elementlərin əlavə olunması. 

HTML4 əsas konstruktiv element `div` elementi idi. 
`div` – özü-özlüyündə səhifədəki düzbucaqlı bir oblastdır hansı ki özündə nəsə saxlayır. (burda hər şey ola bilər)

Problem onda idir ki burda nə gəldi yerləşdirmək olardı və və bəzi hallarda tamamən anlaşılmaz olurdu, səhifədəki hansı funskiya hansı rol daşıyır və hansı məntiqi məna daşıyır. 
Yeganə məntiqli çıxış yolu elementə unikal identifikator (id atributu) əlavə olunması idi.

# HTML5-də div yox olmayıb, ancaq yeni elementlər yaranıb, hansılar ki özü-özlüyündə bir məna daşıyır.

Bunlara misal olaraq:

 article.
 aside
 body HTML.
 footer.
 header.
 hgroup.
 nav
 section.
 h1,h2,h3,h4,h5 и h6.

- Yeni müxtəlif spesefik məsələləri həll edən digər yeni elementlər yaranmışdır.

- Veb-səhifələrin Появилась новая технология построения оглавления веб-страницы (outline).

Теперь для каждой веб-страницы, можно построить его оглавление и увидеть ее карскас или структуру. 
Планируется, что в будущем, эта новая возможность будет внедрятся в браузеры.

- HTML5 yeni qaydalarına görə dil daha ciddiləşib.

HTML4 sintaksis baxımdan çox sərbəst idi.

# HTML 5: отличия от HTML 4

**Синтаксис**

HTML 5 будет иметь два синтаксиса — «custom» HTML и XML. 
HTML синтаксис определяет детализированные правила синтаксического анализа (включая «обработку ошибок»). 
Пользовательские агенты будут следовать этим правилам для документов, имеющих MIME тип text/html. Вот пример синтаксиса HTML:

XML синтаксис совместим с документами XHTML1 и его реализациями. 
Чтобы использовать этот синтаксис нужно объявить MIME тип XML, а элементы должны быть выстроены согласно спецификации XML. 
Ниже приведен пример, который соответствует синтаксису XML:

**Кодировка символов**

Для синтаксиса HTML разработчики могут использовать три способа установки кодировки:

на транспортном уровне. При использовании Content-Type HTTP заголовка, например.
используя символ Unicode Byte Order Mark (BOM) в начале файла. 
Этот символ обеспечивает сигнатуру используемого кодирования.
используя мета тег с атрибутом charset, который должен быть определен как первый дочерний элемент head.
Обратите внимание, что для определения кодировки используется

<meta charset="UTF-8">
вместо
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

Для синтаксиса XML разработчики должны руководствоваться правилами спецификаций XML.

**Новые элементы**

section представляет часть документа или раздел
article представляет независимую часть содержания для включения в документ статей
aside представляет часть содержания, которая только частично связана с остальной страницей
header представляет заголовок section
footer — нижний колонтитул, может содержать информацию об авторе, авторском праве и так далее
nav представляет раздел документа, предназначенный для навигации
dialog может использоваться для выделения диалогов:

figure может использоваться для связи заголовка с медиа контентом:

audio и video для мультимедиа. Оба обеспечивают соответствующий API. 
Таким образом разработчики могут писать скрипты собственного пользовательского интерфейса, но также предусмотрен способ вызова стандартного API пользовательского агента. Вместе с этими элементами может быть использован source, если есть возможность организовать параллельные потоки.
embed используется для контента plugin’ов.
meter — для представления единиц измерений.
time — дата и/или время.
canvas используется для динамической отрисовки графики.
command представляет команду, которую может вызвать пользователь.
datagrid — интерактивное представление списка типа «дерево» или табличных данных.
details представляет дополнительную информацию, которую пользователь может получить по требованию.
datalist вместе с новым атрибутом list используется чтобы сделать combobox:

datatemplate, rule, и nest обеспечивают механизм шаблонов (templating mechanism) для HTML.
event-source используется для перехвата событий, посланных сервером.
output представляет определенный тип вывода, например, от вычислений, сделанных через скрипт.
progress представляет ход выполнения задачи, например, загрузки.

Атрибут type элемента input теперь имеет следующие новые значения:
datetime
datetime-local
date
month
week
time
number
range
email
url
Идея относительно этих новых типов состоит в том, что пользовательский агент может обеспечить интерфейс для таких объектов как календарь (выбор даты), интеграции с адресной книгой и предоставить серверу данные в определенном формате. 
Это дает определенные преимущества как пользователям, так и разработчикам, поскольку пользовательский ввод проверяется перед посылкой на сервер браузером. 
Это означает, что разработчикам нет необходимости расходовать ресурсы на проверку введенных данных, что, в свою очередь, приводит к сокращению времени ожидания ответа.

Новые атрибуты

HTML 5 вводит несколько новых атрибутов для элементов, которые уже входили в HTML 4:

элементы a и area получили новый признак ping, который определяет список URI адресов, которые должны пропинговаться при переходе по гиперссылке. Принцип функционирования пока до конца не ясен.
элемент area теперь имеет атрибуты hreflang и rel
base получил атрибут target
атрибут value для li и атрибут start для элемента ol больше не deprecated
meta получил атрибут charset
новый атрибут autofocus может быть определен у input (кроме тех случаев, когда type атрибут — hidden), select, textarea и button. Это обеспечивает способ передачи управления
форме во время загрузки страницы
атрибут form для input, output, select, textarea, button и fieldset позволяет связать элемент с более чем одной формой
input, button и form получили атрибут replace, который определяет, что будет с элементом после отправки формы
form, select и datalist имеют атрибут data, который учитывает автоматическое предзаполнение, в случае заполнения данными с сервера
новый атрибут required применяется к input (кроме тех случаев, когда type атрибут — hidden, image или кнопка) и textarea. Он указывает обязательные для заполнения поля
input и textarea имеют новый атрибут inputmode, который дает подсказку пользовательскому интерфейсу относительно того, какие данные ожидаются для ввода
теперь можно disable (отключить) сразу целый fieldset, что не было возможно прежде
элемент input имеет несколько новых атрибутов для определения ограничений: autocomplete, min, max, pattern и step, а также list, который может использоваться вместе с элементами select и datalist
input и button также получили новый атрибут template, который может использоваться для шаблонов повторения
элемент menu имеет три новых атрибута: type, label и autosubmit
script имеет новый атрибут async, который влияет на загрузку и выполнение сценария
элемент html имеет новый атрибут manifest, который указывает на кэш приложений, используемый вместе с API для автономных Web приложений
Несколько атрибутов из HTML 4 применяют ко всем элементам, поэтому их называют глобальными атрибутами: class, dir, id, lang, tabindex и title.

Появились также несколько новых глобальных атрибутов:

атрибут contenteditable указывает, что элемент доступен для редактирования
contextmenu может использоваться для указания на контекстное меню, созданное автором
draggable может использоваться вместе с новым drag&drop API
irrelevant указывает, что элемент еще или больше не актуален

Атрибуты для модели повторения (repetition model):

repeat
repeat-start
repeat-min
repeat-max

Отмененные элементы

Следующие элементы не включены в HTML 5, потому что их эффект достигается использованием CSS:

basefont
big
center
font
s
strike
tt
u

Следующие элементы не включенв в HTML 5, потому что их использование негативно сказывалось на удобстве и доступности:

frame
frameset
noframes

Следующие элементы не включены, потому что использовались редко или они могут быть заменены другими элементами:

acronym
applet замещен object
isindex
dir замещен ul
Наконец noscript остался только в синтаксисе HTML, поскольку его использование предполагает разбор с помощью HTML парсера.

Отмененные атрибуты

accesskey для a, area, button, input, label, legend и textarea
rev и charset для link и a
shape и coords для a
longdesc для img и iframe
target для link
nohref для area
profile для head
version для map, img, object, form, iframe, a
scheme для meta
archive, classid, codebase, codetype, declare и standby для object
valuetype и type для param
charset и language для script
summary для table
headers, axis и abbr для td и th
scope для td

Кроме того, HTML 5 не имеет следующих атрибутов, поскольку они лучше обрабатываются CSS:

align для caption, iframe, img, input, object, legend, table, hr, div, h1-h6, p, col, colgroup, tbody, td, tfoot, th, thead, tr и body
alink, link, text и vlink для body
background для body
bgcolor для table, tr, td, th и body
border для table, img и object
cellpadding и cellspacing для table
char и charoff для col, colgroup, tbody, td, tfoot, th, thead и tr
clear для br
compact для menu, ol и ul
frame на table
frameborder приписывают на iframe
height для iframe, td и th
hspace и vspace для img и object
marginheight, marginwidth и scrolling для iframe
noshade для hr
nowrap для td и th
rules для table
size для hr, input и select
style для всех элементов
type для li, ol и ul
valign для col, colgroup, tbody, td, tfoot, th, thead и tr
width для hr, table, td, th, col, colgroup, iframe и pre
API

HTML 5 вводит множество API, которые должны помочь в создании Web приложений. 
Они могут использоваться вместе с новыми элементами.

2D drawing API , который может использоваться с новым элементом canvas
API для проигрывания видео и аудио, который может использоваться с новыми элементами video и audio
выделенная область памяти (Persistent storage) с поддержкой данных в виде ключ / значение и SQL данных
API, который допускает автономную работу web приложений
API, который позволяет web приложений регистрировать себя для определенных протоколов или типов MIME
Editing API в сочетании с новым глобальным атрибутом contenteditable
Drag&drop API в сочетании с атрибутом draggable
Network API
API, который выстраивает историю посещения, чтобы предотвратить нарушение функционирования back кнопки (Этот API имеет необходимые ограничения безопасности)
Cross-document messaging (Передача сообщений между документами)
события сервера (Server-sent events) в сочетании с новым элементом event-source

Расширение HTMLDocument

HTML 5 расширил интерфейс HTMLDocument. 
Интерфейс теперь реализован на всех объектах интерфейса Document. Его новые методы:

getElementsByClassName()
activeElement и hasFocus
getSelection()
designMode и execCommand(), которые используются главным образом для редактирования документов

Расширение к HTMLElement

Интерфейс HTMLElement также получил несколько расширений:

getElementsByClassName()
innerHTML
classList введен для удобства доступа к className. 
Возвращаемый объект имеет методы has(), add(), remove() и toggle() для манипуляции классами элемента
