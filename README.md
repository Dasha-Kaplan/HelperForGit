# HelperForGit *Помошник/справоник по Git, основан на текущих знаниях*

**Запомните**
1. Для обозначения систем контроля версий используют не только аббревиатуру VCS, но и SCM (от англ. Source Control Management — «система управления исходным кодом»).
2. Хранение, изменение и анализ истории — основные функции системы контроля версий.
3. Система контроля версий — общее название ряда продуктов, таких как Git, Mercurial, Subversion и других. Сейчас мы будем говорить о самом популярном из них — Git.
---
- Git используют для синхронизации данных между участниками одной или нескольких команд.
- Git может определить, кто и в какой момент внёс изменения.
- Git позволяет «откатиться» к предыдущим версиям, если что-то пошло не так. 
---
*Git можно установить [здесь](https://git-scm.com/download/win)*

## **Начальные комнады для работы с командной строкой**
Чтобы вывести текущую рабочую директорию, можно использовать команду ```pwd```; <br>
У большинства пользователей компьютера есть доступ к домашней директории. Чтобы к ней перейти, используют команду ```cd ~``` ; <br>
Менять директории командой ```cd```; <br>
Выводить содержимое директорий с помощью ```ls```; <br>
Просматривать содержимое вместе со скрытыми файлами и папками через ```ls -a```; <br>
Команда ```touch``` создаёт файл, а команда ```mkdir``` — директорию. <br>
С помощью флага ```-p``` можно создать целую структуру директорий одной командой: ```mkdir -p``` <br>
Для копирования файлов используют команду ```cp```, для перемещения ```— mv```<br>
Вывести содержимое файла можно командой ```cat```. <br>
Для удаления файла используют ```rm```, для удаления пустой директории — ```rmdir```, а для директории с файлами — ```rm -r``` <br>

## **Для эффективной работы**
* С помощью ```&&``` можно выполнить несколько команд сразу — одну за другой. 
* Команды, которые вы выполняете в консоли, попадают в историю.
* Вы можете перемещаться по истории консоли при помощи стрелок ```↑↓```. 
* При нажатии на ```Tab``` консоль предложит несколько вариантов продолжения команды. 
* Символами ```/``` и ```~``` можно быстро перемещаться к корневой и домашней директориям.

## **Репозитории и коммиты**
- Инициализировать репозиторий можно с помощью команды git init.
- Проверить статус, или состояние, репозитория поможет команда git status.
- Если вы ошиблись и случайно инициализировали не ту папку, можно «разгитить» её — удалить скрытую подпапку .git.
- Команда git add позволяет подготовить файл к сохранению.
- Команда git add --all подготовит к сохранению сразу все файлы.
- С помощью git add . можно добавить в репозиторий текущую папку со всеми файлами.
- Коммит можно сделать с помощью команды git commit.
- Ключ -m позволяет присвоить коммиту сообщение. Помните, что такие сообщения должны быть информативными: чётко описывать изменения.
- В коммит попадает то, что было предварительно добавлено «в корзину», или «в кадр», перед коммитом.
- git log — оглянуться назад и посмотреть коммиты.
