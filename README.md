Описание

Эта программа предназначена для анализа данных о температуре, хранящихся в файле CSV. Она предоставляет различные функциональности для вычисления статистики на основе этих данных. 
Пользователи могут указать входной файл, выбрать отображение статистики для определенного месяца или вычислить общую статистику.

Использование

Программу можно запустить из командной строки. Ниже приведены доступные опции:

-h                       Отобразить справочную информацию
-f <filename.csv>        Указать входной файл CSV для обработки
-m <номер месяца>        Отобразить статистику только для указанного месяца

Функциональность

Отображение справки (-h): При использовании опции -h программа отображает описание своей функциональности и доступные параметры командной строки.
Входной файл (-f): Пользователи должны указать входной файл CSV с помощью опции -f, за которой следует имя файла. Если входной файл не указан, будет выведено сообщение об ошибке, и программа завершится.
Отображение статистики для конкретного месяца (-m): Пользователи могут указать номер месяца с помощью опции -m, чтобы отобразить статистику только для этого конкретного месяца. 
Если эта опция не используется, программа вычислит общую статистику.
