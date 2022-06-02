# Решатель японских кроссвордов


### Запуск программы:

```Console
cabal new-run hw-mathlog2202
```

### Формат ввода:

Программа выведет сообщение **Enter the number of rows:**, после чего надо ввести количество строк кроссворда - натуральное число. 

При некорректном количестве строк программа выведет сообщение **Invalid rows input! All elements must be natural numbers separated by spaces.** и остановит выполнение программы.

Далее программа выведет сообщение **Enter the specified number of lines:**, после чего надо ввести указанное ранее количество строк, где каждая строка - последовательность натуральных чисел, разделенных пробелами. 

При некорректном вводе программа выведет сообщение **Invalid rows input! All elements must be natural numbers separated by spaces.** и остановит выполнение программы.

Далее следует аналогичный ввод столбцов.

В конце ввода программа проверяет, что введенные условия коректны и не противоречат друг другу. При некорректных условиях программа выведет **Invalid rows input! Some line is too long.** или **Invalid colums input! Some line is too long.**


### Формат выывода:




