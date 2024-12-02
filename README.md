# Ангриков Тенгис Владимирович

## БПИ239

### Вариант 20

#### Условие:  Разработать программу, вычисляющую число вхождений различных цифр в заданной ASCII–строке. Вывод результатов организовать в файл (используя соответствующие преобразования чисел в строки).
#### Работу выполнил на 10 баллов на 10 баллов!

### Отчёт:
#### 1) На 4-5:
   - Вводится имя файла со входной строкой.
   - Из файла строка считывается в буфер
   - Запускается подпрограмма подсчета цифр в строке, счетчики хранятся в массиве word.
   - Вводится имя output файла
   - Счетчики цифр записываются через пробел в output файл.
   - Изменяемые параметры не предусмотрены
   - В программе присутствуют комментарии, поясняющие выполняемые ей действия.
   - Обработка данных, полученных из файла сформирована в виде отдельной подпрограммы.
   - В подкаталоге данных присутствуют файлы, используемые для тестирования.
   - Размер буфера поставил 4096
   - При чтении файла размером, превышающим размер буфера,
падение программы не происходит.
#### 2) На 6-7:
   - Внутри функций используются локальные переменные.
   - Ввод и вывод организованы при помощи специальных макросов.
   - Возвращаемые параметры в регистрах a.
#### 3) На 8:
   - Добавил в программу возможность дополнительного вывода результатов на консоль. Выводить или нет решает пользователь отвечая «Y» или «N» на соответствующий вопрос компьютерной программы.
   - Сделал программу тестирования с 3 тестами, через подпрограммы.
#### 4) На 9:
   - В программе использовал макросы для ввода/вывода, подпрограмму обрабработки данных обернул в макрос, а так же использовал многие дургие вспомогательные макросы(например, push и pop)
   - Реализовал вторую тестируюшую подпрограмму, в которой все сделано при помощи макросов, но она почти не отличается от первой, тк большинство методов у меня это макросы(для удобства)
#### 5) На 10:
   - Программа разбита на несколько единиц компиляции.
   - При этом подпрограммы ввода–вывода составляют унифицированные модули, используемые повторно как в программе, осуществляющей ввод исходных данных, так и в тестирующих программах.
   - Все макросы находятся в отдельной макробиблиотеке - macros.asm.
   - Использовал диалоговые окна для получения имен(путей) файлов input и output.
