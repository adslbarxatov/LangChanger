# LangChanger v 1.1u (based on HSDW v 5.2)

A tool for quick fixing wrong keyboard layout selection

Инструмент быстрого исправления раскладки клавиатуры

#

This tool allows you to quickly fix entered text when keyboard layout was selected incorrectly.
For example, text ```Vfvf vskf hfve``` will be changed to ```Мама мыла раму```, and text ```Пщщв ьщктштп```
will be replaced with ```Good morning```. Utility also works with punctuation marks.
Supported directions: ru_ru (0x0419) -> en_us (0x0409), en_us -> ru_ru.

Инструмент позволяет исправлять текст, введённый при ошибочно выбранной раскладке клавиатуры.
Например, текст ```Vfvf vskf hfve``` будет заменён на ```Мама мыла раму```, а текст ```Пщщв ьщктштп``` –
на ```Good morning```. Утилита поддерживает знаки препинания.



## Направления перевода / Translation directions:

```
ru_ru (0x0419) -> en_us (0x0409)
en_us (0x0409) -> ru_ru (0x0419)
```



## Installation / Установка (WinXP, Win7)

It is recommended that you prepare this utility for use. Follow the algorithm presented below:
1. Place LangChanger.exe directly to ```Program files``` or ```Program files (x86)``` directory.
2. Create a shortcut for it on your desktop.
3. Move shortcut to the main menu (it doesn't matter what subfolder you will select).
4. In Main menu do right click on the shortcut and select ```Properties```. Stay in field ```Hotkey```
and set key combination for quick call of utility (f.e., ```Ctrl + Alt + K```). Press ```OK``` button.
However, nothing disallows you to launch the utility directly from the main menu or desktop

Перед использованием утилиту следует подготовить к работе. Для этого:
1. Скопируйте файл LangChanger.exe в папку ```Program files``` или ```Program files (x86)```.
2. Создайте на Рабочем столе ярлык для этого файла.
3. Переместите ярлык в Главное меню (в любую папку).
4. В Главном меню щёлкните правой кнопкой мыши по скопированному ярлыку и выберите меню ```Свойства```.
Установите курсор в поле ```Быстрый вызов``` и нажмите комбинацию клавиш быстрого вызова программы
(например, ```Ctrl + Alt + K```). Нажмите ```OK```.
Впрочем, ничто не мешает запускать эту утилиту из главного меню или с рабочего стола напрямую



## Usage / Использование

1. Select 'bad' text. It is recommended that the first symbol of selected fragment allows to
determine text language (not a digit or a punctuation sign).
2. Copy it to clipboard (```Ctrl + C``` or ```Ctrl + Ins``` or ```right click + Copy```).
3. Call LangChanger (f.e., ```Ctrl + Alt + K```, or directly from the main menu).
4. Paste text backward (```Ctrl + V``` or ```Shift + Ins``` or ```right click + Paste```).

1. Выберите 'плохой' текст. Желательно, чтобы первый символ выделенного фрагмента позволял
однозначно определить язык текста (т.е. это не должна быть цифра или знак препинания).
2. Скопируйте его в буфер обмена (```Ctrl + C``` или ```Ctrl + Ins``` или ```правый щелчок мыши + Копировать```).
3. Запустите LangChanger (например, ```Ctrl + Alt + K```, или напрямую из главного меню).
4. Вставьте текст обратно (```Ctrl + V``` или ```Shift + Ins``` или ```правый щелчок мыши + Вставить```).



## Features / Дополнительные возможности

This tool can make copy and paste operations by himself (with switching of current window). If you specify
```-f``` flag after the executable's name in shortcut's properties (f.e.,
```"C:\Program files\LangChanger.exe" -f```), this option will be activated. But some applications may
incorrectly react to this option

Утилита может выполнять операции копирования и вставки самостоятельно (с переключением текущего окна).
Если Вы укажете флаг ```-f``` после имени программы в настройках ярлыка (например,
```"C:\Program files\LangChanger.exe" -f```), эта опция станет активной. Однако некоторые приложения
могут некорректно реагировать на работу этой функции



## Requirements / Требования

Needs Windows XP or newer / Требует Windows XP или новее



## Development policy and EULA / Политика разработки и EULA

This [Policy (ADP)](https://vk.com/@rdaaow_fupl-adp), its positions, conclusion, EULA and application methods
describes general rules that we follow in all of our development processes, released applications and implemented
ideas.
**It must be acquainted by participants and users before using any of laboratory's products.
By downloading them, you agree to this Policy**

Данная [Политика (ADP)](https://vk.com/@rdaaow_fupl-adp), её положения, заключение, EULA и способы применения
описывают общие правила, которым мы следуем во всех наших процессах разработки, вышедших в релиз приложениях
и реализованных идеях.
**Обязательна к ознакомлению всем участникам и пользователям перед использованием любого из продуктов лаборатории.
Загружая их, вы соглашаетесь с этой Политикой**
