Семинары по Основам ОС (годовой курс "Компьютерные технологии").
---------------------------------------------------------------------------------

Семинар 1: 

Введение. Функции и задачи ОС. Что будет и чего не будет в курсе. 

Командная строка. Встроенная справка (MANual pages).

Интерфейс системных вызовов. Библиотека (g)libc. 

Структура линкуемого исполняемого (ELF)-файла. 

LD и постановка программы на исполнение. Создание процесса.

Практика:

Пример собственной реализации функции-обертки над системным вызовом.

Примеры программ fork, wait, waitpid, exit, exec*.


Семинар 2:
- частотный анализ системных вызовов
- диаграмма состояний процесса

- оверхед на системный вызов
- методики измерения времени

- read/write--обеспечивают в штатных сценариях, но не гарантируют целостную передачу за 1 вызов. Решение — обернуть в циклы.
- pipe,FIFO, cmd pipeline
- ремарка о двусторонних пайпах

- парсинг аргументов командной строки.
- ремарка о реэнтерабельности
- пример: fork, exec, n-1 pipes
- домашка #1
- Не успели: 
  --Пример "reap zombies"
  -- strtok, ремарка о реэнтерабельности.

