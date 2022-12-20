# TurboTasks
## Задачи для начинающих и не очень программистов

### Легкий уровень
 - Игра "больше меньше".
   - Загадывается число от 1 до 1000, задача игрока - угадать число за 10 попыток.
 - Подсчет "дырочек" в тексте.
   - Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек.
 - Приложение заменяющие все "Л" на "Р" в тексте, (анимезиция).
   - Компилятор сломался -> Компирятор сромарся.
 - Приложение "Генератор паролей".
   - Можно задать длину, используемые символы и на выходе получить пароль.
 - Другие задачи.
   - Задачи [отсюда](http://pascalabc.net/downloads/Books/Rubantsev/InterestLessPas.pdf), [отсюда](http://pascalabc.net/downloads/Books/Rubantsev/InterestProjProjects.pdf), [отсюда](http://pascalabc.net/downloads/Books/Rubantsev/SFML.pdf).
   - [1000 задач](http://ptaskbook.com/ru).
   - [Задачи/алгоритмы](http://algolist.ru).

### Средний уровень
 - Нормальные крестики-нолики.
 - Игра "Жизнь Конвея".
 - Размытие картинок алгоритмом Box Blur.
 - Рисовалка типа "Paint".
 - Игра "Змейка".
 - Игра "Тетрис".
 - Telegram-bot для подсчета "дырочек" в тексте.
   - Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек.
 - Игра "Виселица".
   - Задается рандомное слово и показывается его количество букв, задача игрока - отгадать слово по буквам за 7 попыток.

### Сложный уровень
 - Птичка типа "Flappy Bird".
 - Игра 2048.
 - Игра Сапёр.
 - Подсчет "дырочек" в тексте. Усложнённая версия.
   - Подсчёт дырочек должен производиться для произвольных символом (Например в слоге "ロ" - 1 дырочка).
 - Дизеринг изображений.
   - [пример](https://github.com/turborium/Dither3)
 - Приложение заменяющие все "Л" на "Р" в тексте, и озвучивающее результат.
   - компилятор сломался -> компирятор сромарся [пример](https://github.com/turborium/microsoft-text-to-speech-delphi-example)

### Очень сложно.
 - Калькулятор (без готового парсера, скобок и т.д.). Проверяю на стриме.
   - Все уверены, что написать простейший калькулятор - очень просто. Однако просмотр ютуб роликов вида "пишем калькулятор на языке xxx" показал, что в действительности написать хороший, не глючный калькулятор - очень сложно.
   - Условия:
     - Калькулятор должен иметь UI/GUI/графический интерфейс.
     - Калькулятор должен быть "простейшим" - никаких eval("1+3\*2") и прочих парсеров математических выражений. Просто имитация самого дешевого калькулятора. Т.е. после нажатия [1] [+] [3] [\*] [2] [=] должно получиться 8, а не 7.
     - Язык/среда и т.д. - любые.
     - Желательны следующие функции: +,-,\*,/,корень,очистка,точка,удаление символа.
     - **Важное уточнение - количество цифр на «экране» должно быть ограниченным, т.е. например ввести можно не более 15 цифр. Не должен происходить переход в форму вида 2.43847e16 при вводе большего количества цифр.**
   - Критерии оценки:
     - Главное: не глючность.
     - Не главное: качество кода.
     
### КИБЕРПСИХОЗ🤪 (НЕ СТОИТ)
 - Парсер математических выражений вида "4+5*2".
   - [пример](https://github.com/turborium/SimpleMathParser).
 - Интерпритатор любого языка программирования. (не изотерического - типо brainfuck)  
   - [пример](https://github.com/turborium/turboriumbasic).
---
### Список выполненных задач.
 - Подсчет "дырочек" в тексте.
   - https://github.com/ketchuup/Holes
   - https://github.com/Fikerus/holes
   - https://gist.github.com/rprtr258/ae549c12fbcbb7c70542ec3a8d4072a8
   - https://github.com/osennij-morok/dyrochki (+)
   - https://github.com/ketchuup/Holes
 - Подсчёт "дырочек" в произвольном тексте.
   - https://github.com/ketchuup/Any (+/-)
   - https://github.com/Fikerus/holes-canvas (+)
 - Приложение заменяющие все "Л" на "Р" в тексте.
   - https://github.com/BohdanLiuisk/kal-prilozhenie/blob/main/Program.cs
 - Приложение заменяющие все "Л" на "Р" в тексте с озвучкой.
   - https://github.com/LeenzeryDev/Animezator/
   - https://github.com/cloudlyhimo/tts_repl_py
 - Игра "Змейка".
   - https://github.com/rolexxxandr/snake-pygame
   - https://github.com/Vertiigor/Snake
   - https://github.com/a1excoder/AlexSnake
 - Игра "Жизнь Конвея".
   - https://github.com/rolexxxandr/conways-game
   - https://github.com/Vertiigor/Conway-Life
 - Telegram-bot для подсчета "дырочек" в тексте.
   - https://github.com/rolexxxandr/holes-tgbot
 - Интерпритатор любого языка программирования.
   - https://github.com/Vertiigor/BrainFuck
- Игра "Виселица".
   - https://github.com/rolexxxandr/hangman
