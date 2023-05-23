# 🐍 Python За 30 Дней

|# День | Темы                                                     |
|------|:---------------------------------------------------------:|
| 01  |  [Знакомство с Python](./readme.md)|
| 02  |  [Variables, Built-in Functions](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)|
| 03  |  [Operators](./03_Day_Operators/03_operators.md)|
| 04  |  [Strings](./04_Day_Strings/04_strings.md)|
| 05  |  [Lists](./05_Day_Lists/05_lists.md)|
| 06  |  [Tuples](./06_Day_Tuples/06_tuples.md)|
| 07  |  [Sets](./07_Day_Sets/07_sets.md)|
| 08  |  [Dictionaries](./08_Day_Dictionaries/08_dictionaries.md)|
| 09  |  [Conditionals](./09_Day_Conditionals/09_conditionals.md)|
| 10  |  [Loops](./10_Day_Loops/10_loops.md)|
| 11  |  [Functions](./11_Day_Functions/11_functions.md)|
| 12  |  [Modules](./12_Day_Modules/12_modules.md)|
| 13  |  [List Comprehension](./13_Day_List_comprehension/13_list_comprehension.md)|
| 14  |  [Higher Order Functions](./14_Day_Higher_order_functions/14_higher_order_functions.md)|     
| 15  |  [Python Type Errors](./15_Day_Python_type_errors/15_python_type_errors.md)| 
| 16 |  [Python Date time](./16_Day_Python_date_time/16_python_datetime.md) |     
| 17 |  [Exception Handling](./17_Day_Exception_handling/17_exception_handling.md)|    
| 18 |  [Regular Expressions](./18_Day_Regular_expressions/18_regular_expressions.md)|    
| 19 |  [File Handling](./19_Day_File_handling/19_file_handling.md)|
| 20 |  [Python Package Manager](./20_Day_Python_package_manager/20_python_package_manager.md)|
| 21 |  [Classes and Objects](./21_Day_Classes_and_objects/21_classes_and_objects.md)|
| 22 |  [Web Scraping](./22_Day_Web_scraping/22_web_scraping.md)|
| 23 |  [Virtual Environment](./23_Day_Virtual_environment/23_virtual_environment.md)|
| 24 |  [Statistics](./24_Day_Statistics/24_statistics.md)|
| 25 |  [Pandas](./25_Day_Pandas/25_pandas.md)|
| 26 |  [Python web](./26_Day_Python_web/26_python_web.md)|
| 27 |  [Python with MongoDB](./27_Day_Python_with_mongodb/27_python_with_mongodb.md)|
| 28 |  [API](./28_Day_API/28_API.md)|
| 29 |  [Building API](./29_Day_Building_API/29_building_API.md)|
| 30 |  [Conclusions](./30_Day_Conclusions/30_conclusions.md)|

🧡🧡🧡 HAPPY CODING 🧡🧡🧡


<div align="center">
  <h1> Python за 30 дней: День 1 - Знакомство с Python</h1>

  <sub>Автор:
  <a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
  <small> Второе издание: июль, 2021</small>
  </sub>
</div>


[День 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)

![Python за 30 дней](./images/30DaysOfPython_banner3@2x.png)

- [🐍 Python за 30 дней](#-python-за-30-дней)
- [📘 День 1](#-день-1)
  - [Приветствие](#приветствие)
  - [Знакомство с Python](#знакомство-с-python)
  - [Почему Python?](#почему-python-)
  - [Установка среды](#установка-среды)
    - [Установка Python](#установка-python)
    - [Python Shell](#python-shell)
    - [Установка Visual Studio Code](#установка-visual-studio-code)
      - [Как пользоваться visual studio code](#как-пользоваться-visual-studio-code)
  - [Основы Python](#основы-python)
    - [Синтаксис Python](#синтаксис-python)
    - [Отступы в Python](#отступы-в-python)
    - [Комментарии](#комментарии)
    - [Типы данных](#типы-данных)
      - [Числа](#числа)
      - [Строки](#строки)
      - [Булевые значения](#булевые-значения)
      - [Список](#список)
      - [Словарь](#словарь)
      - [Кортеж](#кортеж)
      - [Множество](#множество)
    - [Проверка типа данных](#проверка-типа-данных)
    - [Файл Python](#файл-python)
  - [💻 Упражнения - День 1](#-упражнения---день-1)
    - [Упражнения: Уровень 1](#упражнения-уровень-1)
    - [Упражнения: Уровень 2](#упражнения-уровень-2)
    - [Упражнения: Уровень 3](#exercise-level-3)

# 📘 День 1

## Приветствие

**Поздравляю и добро пожаловать!** Раз вы здесь, значит вы решились бросить себе вызов и присоединиться к нам в изучении _Python за 30 дней_. Из уроков вы узнаете всё необходимое, чтобы программировать на python, и поймете, что вообще программирование из себя предсталвяет. После успешного выполнения программы вы получите сертификат _30DaysOfPython_.

Для активного участия при желании можете вступить в чат в telegram: [30DaysOfPython challenge](https://t.me/ThirtyDaysOfPython).  

## Знакомство с Python

Python - это высокоуровневый язык программирования общего назначения. Python - язык open source (с открытым исходным кодом), а также интерпретируемый и объектно-ориентированный. Создатель Python - Гвидо ван Россум, нидерландский программист. Название данного языка программирования заимствовано из британского комедийного скетч-сериала, *Летающий цирк Монти Пайтона*. Первая версия вышла 20 февраля 1991 года. Челлендж **Python за 30 дней** постепенно познакомит вас с последней версией Python - Python 3. Темы разделены на 30 блоков на 30 дней соответственно. В каждом из них вы найдете объяснение темы доступным языком, реальные примеры и множество упражнений для практики.

Данный челлендж предназначен для интересующихся языком программирования python: от начинающих до профессионалов. Его изучение может занять у вас от 30 до 100 дней. Активные участники чата в telegram имеют все шансы справиться успешно.

Материал написан простым языком. **Python за 30 дней** поможет вам активно влиться в процесс изучения и поддерживать мотивацию, однако без ваших стараний не обойтись. Вам потребуется отвести на занятия много времени, чтобы успешно освоить программу. Тем, кто предпочитает воспринимать информацию визуально, рекомендую обратить внимание на видео-уроки на YouTube-канале <a href="https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw"> Washera</a>. Для начала посмотрите видео [Python for Absolute Beginners video](https://youtu.be/OCCWZheOesI). Подписывайтесь на канал, оставляйте комментарии и задавайте вопросы. Автор обязательно заметит вашу активность.

Автору важно знать ваше мнение. Здесь можно оставить отзыв: [ссылка](https://testimonial-vdzd.onrender.com/)

## Почему Python?

Это язык программирования, очень близкий к языку человеческому. За счет этого понимать его и работать с ним довольно просто.
Python используется в работе крупных компаний(включая Google). Он применяется для разработки веб-приложений, десктопных приложений, а также для системного администрирования и машинного обучения. Python широко распространен среди датасаентистов и специалистов по машинному обучению. Надеюсь, этого достаточно, чтоб убедить вас начать свой путь в изучении Python. Python захватывает мир: либо вы укротите его, либо он вас.

## Установка среды

### Установка Python

Для запуска кода на python вам необходимо его установить: [ссылка](https://www.python.org/).

Пользователям windows: нажмите на кнопку, обведенную красной рамкой.

[![установка на Windows](./images/installing_on_windows.png)](https://www.python.org/)

Пользователям macOS: нажмите на кнопку, обведенную красной рамкой.

[![установка на macOS](./images/installing_on_macOS.png)](https://www.python.org/)

Проверьте, что python установлен: введите в терминал следующую команду:

```shell
python --version
```

![Python Version](./images/python_versio.png)

Я сейчас использую версию _Python 3.7.5_, это видно в терминале. У вас может быть установлена другая версия, но она должна быть не ниже 3.6. Если вы видите у себя в терминале версию python, значит всё отлично. Python установлен на ваше устройство. Двигаемся дальше.

### Python Shell

Python - интерпретируемый скриптовый язык, он не требует компиляции. Это означает, что код выполняется строка за строкой. Python работает при помощи _Python Shell (Python Interactive Shell)_: выполняются команды, написанные на python, и мы получаем результат.

Для работы Python Shell нужен код на языке Python от пользователя. Вы вводите код, он интерпретируется, и в следующей строке появляется результат.
Откройте свой терминал или командную строку и введите:

```shell
python
```

![Python Scripting Shell](./images/opening_python_shell.png)

Python Shell готов к работе, осталось лишь написать код. После символа >>> вводите свой код и нажимайте Enter.
Время написать наш первый код!

![Python script on Python shell](./images/adding_on_python_shell.png)

Поздравляю, вы написали свой первый код на языке Python в Python Shell. Как же теперь его закрыть?
После символа >> введите команду **exit()** и нажмите Enter.

![Exit from python shell](./images/exit_from_shell.png)

Теперь вы умеете открывать и закрывать Python Shell.

Python выдаст вам результат только в случае отсутствия ошибок, то есть если Python понимает ваш код. Давайте специально допустим ошибку и посмотрим, что вернет нам Python.

![Invalid Syntax Error](./images/invalid_syntax_error.png)

Как видите, Python настолько умный, что он сам понимает, какую ошибку мы допустили: _Syntax Error: invalid syntax_. Использовать символ x для перемножения в Python неправильно, это синтаксическая ошибка. Вместо символа (**x**) для перемножения используется звездочка (*). Ошибка, которую вернул нам Python, четко дает понять, что именно нужно исправить.

Процесс обнаружения и устранения ошибок в программе назывется *отладкой*. Давйте исправим ошибку, поставив звездочку * на место символа **x**.

![Fixing Syntax Error](./images/fixing_syntax_error.png)

Ошибка устранена, код работает и приводит к нужному результату. При работе программистом вы будете встречаться с подобными ошибками постоянно. Важно знать, как их исправлять. Для этого необходимо научиться понимать, с какими ошибками вы сталкиваетесь. Например, вот такие ошибки вы можете встретить в случае с Python: *SyntaxError*, *IndexError*, *NameError*, *ModuleNotFoundError*, *KeyError*, *ImportError*, *AttributeError*, *TypeError*, *ValueError*, *ZeroDivisionError* и др. Больше различных **_видов ошибок_** в Python мы рассмотрим в следующих разделах.

Время ещё попрактиковаться в использовании Python Shell! Откройте терминал или командную строку и введите слово **python**.

![Python Scripting Shell](./images/opening_python_shell.png)

Вы открыли Python Shell. Давайте попробуем выполнить простые математические операции (сложение, вычитание, умножение, деление, деление по модулю, возведение в степень).

Прежде чем начать писать код, для начала вспомним основы математики:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

В python есть дополнительные операции:

- 3 % 2 = 1 => для нахождения остатка от деления
- 3 // 2 = 1 => для нахождения целой части от деления

Теперь превратим математические выражения в код на Python. Напишем комментарий в самом начале Python Shell. 

_Комментарий_ - это часть кода, которую python не выполняет. Так что мы можем добавить в наш код текст, чтобы сделать его более читаемым. Комментарии в python начинаются со знака решетки (#).
Вот так пишутся комментарии в python:

```shell
 # комментарий начинается со знака решетки
 # это комментарий, т.к. он начинается со знака решетки (#)
```

![Математика в python shell](./images/maths_on_python_shell.png)

Прежде чем перейти к следующему разделу, давайте еще потренируемся работать с Python Shell. Введите команду _exit()_ и закройте Python shell, затем откройте заново и приступайте к практике. 

![Пишем на python shell](./images/writing_string_on_shell.png)

### Установка Visual Studio Code

Python Shell хорошо подойдет для проверки короткого кода, но не для большого проекта. На самом деле разработчики используют разные редакторы кода для работы. На протяжении этих 30 дней мы будем пользоваться visual studio code. Visual studio code - популярный open source текстовый редактор. Мне очень нравится vscode, рекомендую его [установить](https://code.visualstudio.com/). Если вы предпочитаете работать в других редакторах, это ваше право. Главное, чтобы вам было комфортно.

[![Visual Studio Code](./images/vscode.png)](https://code.visualstudio.com/)

Если вы уже установили visual studio code, давайте разберемся, как им пользоваться.
Тем, кто предпочитает видео-формат, советую подписаться на Visual Studio Code for Python: [Video tutorial](https://www.youtube.com/watch?v=bn7Cx4z-vSo)

#### Как пользоваться visual studio code

Дважды кликните на ярлык visual studio code, чтоб открыть его. Вы увидите такой интерфейс: попробуйте навести курсором на выделенные иконки. 

![Visual studio Code](./images/vscode_ui.png)

Создайте на рабочем столе папку PythonЗа30Дней. Затем откройте её в visual studio code.

![открытие проекта в Visual studio](./images/how_to_open_project_on_vscode.png)

![открытие проекта](./images/opening_project.png)

Когда проект будет открыт, вы увидите специальные значки для создания файлов и папок внутри директории вашего проекта 30DaysOfPython. Ниже вы увидите, что я создал свой первый файл: helloworld.py. Попробуйте сделать то же самое.

![Создание файла python](./images/helloworld.png)

После того, как вы целый день провели за работой с кодом, вам хочется уже наконец закрыть этот редактор, правда? Вот, как можно закрыть открытый проект.

![закрытие проекта](./images/closing_opened_project.png)

Поздравляю, вы завершили установку среды разработки. Пора приступать к коду.

## Основы Python

### Синтаксис Python

Код на языке Python можно писать при помощи Python shell или редактора кода. Файлы Python имеют следующее разрешение: .py.

### Отступы в Python

Отступ представляет собой добавление пробела в текст. Во многих языках они используются, чтобы сделать код более читаемым. Однако в Python у отступов есть особая миссия. Это формирование блоков кода. В других языках программирования эту функцию выполняют фигурные скобки. Ошибки в расстановке отступов - одни из самых часто встречающихся в работе с python.

![Indentation Error](./images/indentation.png)

### Комментарии

Комментарии - это незаменимый инструмент, который позволяет сделать код более читаемым, добавив в него текстовые примечания. Закомментированная часть кода в Python интерпретироваться и запускаться не будет.
Любой текст, начинающийся с решетки(#) в Python - это комментарий.

**Пример: однострочный комментарий**

```shell
    # Это первый комментарий
    # Это второй комментарий
    # Python захватывает мир
```

**Пример: многострочный комментарий**

Для многострочного комментария можно использовать тройные кавычки, если результат не присваивается какой-либо переменной.

```shell
"""Это многострочный комментарий
многострочный комментарий содержит несколько строк.
python захватывает мир
"""
```

### Типы данных

В языке Python различают несколько типов данных. Начнем с самых распространенных. Более подробно мы рассмотрим разные типы данных в следующих разделах. сейчас давайте просто пробежимся по типам данных и познакомимся с ними. На данном этапе вам необязательно иметь четкое понимание того, о чем пойдет речь. 

#### Числа

- Integer: Целые(отрицательные и положительные числа, ноль) числа
    Примеры:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: Вещественное число
    Примеры:
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
    Примеры:
    1 + j, 2 + 4j

#### Строки

Это набор одного или более символов в одинарных или двойных кавычках. Для строки из нескольких фраз используются тройные кавычки.

**Примеры:**

```py
'Asabeneh'
'Финляндия'
'Python'
'Мне нравится преподавать'
'Надеюсь, вам нравится ваш первый день с PythonЗа30Дней'
```

#### Булевые значения

Значением булевого типа данных может быть True либо False. Буквы T и F обязательно должны быть заглавными.

**Примеры:**

```python
    True  #  Свет включен? Если да, значение будет True
    False # Свет включен? Если нет, значение будет False
```

#### Список

Список в Python - это упорядоченная коллекция, в которой можно хранить объекты разных типов данных. Суть похожа на списки (array) в JavaScript.

**Примеры:**

```py
[0, 1, 2, 3, 4, 5]  # все объекты одного типа данных - это список чисел
['Банан', 'Апельсин', 'Манго', 'Авокадо'] # все объекты одного типа данных - это список строк (с названиями фруктов)
['Финляндия','Эстония', 'Швеция','Норвегия'] # все объекты одного типа данных - это список строк (с названиями стран)
['Банан', 10, False, 9.81] # разные типы данных в списке - строка(string), целое число(integer), булевый тип(boolean) и вещественное число(float)
```

#### Словарь

Словарь в Python - это неупорядоченная коллекция данных, которые хранятся в формате пар ключ-значение.

**Примеры:**

```py
{
'first_name':'Asabeneh',
'last_name':'Yetayeh',
'country':'Finland', 
'age':250, 
'is_married':True,
'skills':['JS', 'React', 'Node', 'Python']
}
```

#### Кортеж

Кортеж - это упорядоченная коллекция разных типов данных, как и список. Отличие кортежей в том, что они неизменяемые. Это значит, что после создания кортежа в нем ничего изменить нельзя.

**Примеры:**

```py
('Asabeneh', 'Павел', 'Брук', 'Авраам', 'Лидия') # Имена
```

```py
('Земля', 'Юпитер', 'Нептун', 'Марс', 'Венера', 'Сатурн', 'Уран', 'Меркурий') # планеты
```

#### Множество

Множество - это коллекция типов данных, напоминающая списки и кортежи. В отличие от них, множество - неупорядоченная коллекция. Как и в математике, в множествах в Python хранятся только уникальные объекты.

В следующих разделах мы детально рассмотрим все-все типы данных в Python.

**Примеры:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # в множестве порядок не имеет значения
```

### Проверка типа данных

Для проверки типа данных существующей переменной используется функция **type**. В терминале ниже вы увидите разные типы данных:

![проверка типа данных](./images/checking_data_types.png)

### Файл Python

Для начала откройте вашу папку с проектом 30DaysOfPython. Если вы ее все еще не создали, то сейчас самое время. Внутри этой папки создайте файл helloworld.py. Теперь давайте повторим то, что мы делали в python shell, уже в visual studio code.

В Python shell ответ выводился и без использования **print**. Чтобы увидеть результат в visual studio code, необходимо использовать встроенную функцию *print()*. Встроенная функция *print()* принимает на вход один или более аргументов: *print('аргумент1', 'аргумент2', 'аргумент3')*. Ниже вы увидите примеры.

**Примеры:**

Название файла - helloworld.py

```py
# День 1 - PythonЗа30Дней

print(2 + 3)             # сложение(+)
print(3 - 1)             # вычитание(-)
print(2 * 3)             # умножение(*)
print(3 / 2)             # деление(/)
print(3 ** 2)            # возведение в степень(**)
print(3 % 2)             # деление по модулю(%)
print(3 // 2)            # целочисленное деление(//)

# Проверка типа данных
print(type(10))          # Int (целое число)
print(type(3.14))        # Float (вещественное число)
print(type(1 + 3j))      # Complex number (сложное число)
print(type('Asabeneh'))  # String (строка)
print(type([1, 2, 3]))   # List (список)
print(type({'name':'Asabeneh'})) # Dictionary (словарь)
print(type({9.8, 3.14, 2.7}))    # Set (множество)
print(type((9.8, 3.14, 2.7)))    # Tuple (кортеж)
```

Ниже вы увидите, как запустить код из файла python. Это можно сделать как нажатием зеленой кнопки в Visual Studio Code, так и вводом в терминал *python helloworld.py*.

![запуск кода на python](./images/running_python_script.png)

🌕  Вы отлично справляетесь! Вы только что завершили первый день челленджа, а значит вы уже на верном пути к совершенству. А теперь потренируйте мышцы вашего мозга: выполните парочку упражнений. 

## 💻 Упражнения - День 1

### Упражнения: Уровень 1

1. Проверьте используемую вами версию python
2. Откройте python shell и выполните следующие операции. В качестве операндов используйте 3 и 4.
   - сложение(+)
   - вычитание(-)
   - умножение(\*)
   - деление по модулю(%)
   - деление(/)
   - возведение в степень(\*\*)
   - целочисленное деление(//)
3. Задайте строки в python shell. Строки должны быть следующими:
   - Ваше имя
   - Ваша фамилия
   - Ваша страна
   - Я рад 30 дней изучать python
4. Произведите проверку типов данных:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Asabeneh', 'Python', 'Finland']
   - Ваше имя
   - Ваша фамилия
   - Ваша страна

### Упражнения: Уровень 2

1. Внутри папки 30DaysOfPython создайте папку day_1. В папке day_1 создайте файл python под названием helloworld.py и повторите вопросы 1, 2, 3, 4. Не забывайте использовать _print()_ при работе с файлом python. Перейдите в директорию с вашим файлом и запустите код.

### Упражнения: Уровень 3

1. Запишите примеры разных типов данных в Python: числа(целые, вещественные, сложные), строки, булевые значения, список, кортеж, множество и словарь.
2. Найдите [Евклидово расстояние](https://en.wikipedia.org/wiki/Euclidean_distance#:~:text=In%20mathematics%2C%20the%20Euclidean%20distance,being%20called%20the%20Pythagorean%20distance.) между (2, 3) и (10, 8)

🎉 ПОЗДРАВЛЯЮ ! 🎉

[День 2 >>](./02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
