Привет, GitHub и мир
Hello
# *Инструкция для работы с GIT*

* git init - инициализация локального репозитория
* git status - получить информацию о Git, о его текущем состоянии
* git add - добавить файл или папку к следующему коммиту
* git commit -m "комментарий" - команда по созданию коммита
* git log - вывод на экран истории всех коммитов с их хеш-кодом
* git checkout - переход от одного коммита к другому
* git checkout master - вернуться к актуальному состоянию и продолжить работу

* git diff - увидеть разницу между текущим файлом и закоммиченным файлом

# Cправочные материалы по Markdown

### Markdown - [облегчённый язык разметки](https://ru.wikipedia.org/wiki/%D0%AF%D0%B7%D1%8B%D0%BA_%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%82%D0%BA%D0%B8#%D0%9E%D0%B1%D0%BB%D0%B5%D0%B3%D1%87%D1%91%D0%BD%D0%BD%D1%8B%D0%B5_%D1%8F%D0%B7%D1%8B%D0%BA%D0%B8_%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%82%D0%BA%D0%B8 "Узнать о облегчённом языке разметки"), созданный с целью форматирования в простом тексте, с мксимальным сохранением его читаемости человеком, и пригодным для машинного преобразования в языки для продвинутых публикаций.

Зачем это нужно:

- **Добавлеение разметки туда, где невозможна реальная разметка.** *Например, в простом текстовом файле или в тех же СМС, где невозможно выделение жирным, создание заголовком, выделение цитат и пр.*
- **Для удобного написания текстов для последующей конвертации в *HTML* или другие форматы.**

#### Единого стандарта не существует и разные версии Markdown могут отличаться в деталях. Но базовые элементы из списка ниже поддерживаются во всех стандартах. <u>~~Никогда не пользуйтесь Markdown~~ (it's a joke)</u>
![](smile.png)

Широко используется для написания документации и README-файлов.

Кроме традиционного Markdown у разработчиков получил распространение дополненный  и улучшеный варинат языка - *Github Flavoured Markdown*, сокращённо [***GFM***](https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax "Ссылка для ознакомления").

### Основые отличия ***GFM*** и чистого ***Маркдаун***
- добавили таблицы, которых не было в оригинальном ***Маркдауне**
- добавили альтернативный синтаксис для вставки блоков кода: *теперь можно  не ставить 4 прьлеал перед каждой строкой кода, также можно явно указать язык кода;*
- добавили ~~зачёркнутый~~ текст

[Полный список отличий](https://docs.github.com/ru/get-started/writing-on-github) на ГитХабе.



## Апострофы и кавычки 
Вводятся коды & #8220; & #8221;вводятся без пробелов
* &#8220; Кавычки (левая и правая соответственно) &#8221;
* &#8217; апостроф (справа и слева соответственно) &#8216;

## Блоки цитирования
Вводится одинарная или двойная стрелочка >, >>

* "> Блок цитирования отображается так"

* ">> Ещё одни блог цитирования"


## Полужирное начертание
* Ставятся двойные (**) звёздочки или двойное нижнее подчёркивание (__)


** **полужирное начертание** ** (без пробела)

__ __полужирное начертание__ __ (без пробела)

* Для курсив одинарные звёздочки по бокам.

*курсив*

* Для полужирного курсива (***) тройные звёздочки

***полужирное начертание и курсив*** 

## Нумерованные и ненумерованные списки
* Ставиться любая цифра и точка после нёё:

*1. Перечисление

*1. Цифра с точкой
1. Перечисление
1. Цифра с точкой

* Любой знак (минус, плюс, звезда перед словом, но что-то одно, если список больше двух элеметов)

Выглядить так : - минус

Выглядить так : + минус

Выглядить так : * минус


* * через пробел - белая точка

## Вставка картинки

*  Нужно вставить такую структуру "воскл. знак/квадр. скобки /*Комментарий*/ квадр. скобки/(в скобках путь к файлу сугубо из репозитория.png)
![These are dices!](PNG.png)
 
 ## Горизонтальная линия
 
 *** 
 Для горизонтальной линии нужно поставить 3-и звёздочки, либо 3 нижних подчёркивания (***,___)


 ## Введение ссылок в текст
 Нужно в квадртных скобках внести отобржение ссылки, а саму ссылку в круглые скобки. Также в круглых скобках, в кавычках, можно ввести информацию, для отображения при наведении на ссылку.
 Это выглядит так:

 I like search engine [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy") - ссылка на ресурс

Ещё ссылки можно заключать в "стрелокчки" <...> для их кликабельности. Быстрое введение ссылок:

<http://duckduckgo.com>

<antracidin@mail.com> 
# Basic Git_command

### __git diff__
---
+ **git diff** - Команда _**git diff**_ используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей копией и индексом (собственно _**git diff**_), разница между индексом и последним коммитом (_**git diff --staged**_), или между любыми двумя коммитами (_**git diff master branchB**_).
### __git reset__
---
+ Команда __*git reset*__, как можно догадаться из названия, используется в основном для 
отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса. Также эта 
команда может изменить файлы в рабочем каталоге при использовании параметра __*--hard*__, 
что может привести к потере наработок при неправильном использовании, так что убедитесь в 
серьёзности своих намерений прежде чем использовать его.
### __git rm__
---
+ Команда __*git rm*__ используется в Git для удаления файлов из индекса и рабочей копии. Она похожа на __*git add*__ с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита.
### __git stash__
---
+ Команда __*git stash*__ используется для временного сохранения всех незафиксированных изменений с целью очистки рабочего каталога без необходимости фиксировать незавершённую работу в текущей ветке.
### __git remote__
---
+ Команда __*git remote*__ служит для управления списком удалённых репозиториев. Она позволяет сохранять длинные URL репозиториев в виде понятных коротких строк, например «origin», так что вам не придётся забивать голову всякой ерундой и набирать её каждый раз для связи с сервером. Вы можете использовать несколько удалённых репозиториев для работы и __*git remote*__ поможет добавлять, изменять и удалять их.
### __git clone__
---
+ Команда для получения копии существующего Git-репозитория, например, проекта, в который мы хотим внести свой вклад. Клонирование репозитория осуществляется командой __*git clone <ссылка на репозиторий>*__. Для того, чтобы клонировать репозиторий в каталог с именем, отличающимся от того, что на удалённом репозитории, необходимо указать имя, как параметр строки __*git clone <ссылка на репозиторий> <имя каталога>*__. Т.е. клонированный репозиторий со своим названием.
### __git push__
---
+ Команда __*git push*__ используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию. *Запушить* - значит загрузить на удалённый репозиторий.
### __git pull__
---
+ Команда __*git pull*__ работает как комбинация команд __*git fetch*__ и __*git merge*__, т. е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.
### __Создание ответвлений (fork)__
---
+ Чтобы внести свой вклад в уже существующие проекты, в которых у нас нет прав на внесения изменений путём отправки (*push*) изменений, мы можем создать своё собственное ответвление (*fork*) проекта. Это означает, что GitHub создаст нашу собственную копию проекта, данная копия будет находиться в нашем пространстве имён и вы сможем легко делать изменения путём отправки (*push*) изменений.
---
Рабочий процесс с GitHub обычно работает:
1. Создайте форк проекта.
2. Создайте тематическую ветку на основании ветки *master*.
3. Создайте один или несколько коммитов с изменениями, улучшающих проект.
4. Отправьте эту ветку в ваш проект на GitHub.
5. Откройте запрос на слияние на GitHub.
6. Обсуждайте его, вносите изменения, если нужно.
7. Владелец проекта принимает решение о принятии изменений, либо об их отклонении.
8. Получите обновлённую ветку *master* и отправьте её в свой форк.