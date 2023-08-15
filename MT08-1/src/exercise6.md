# grep и diff

Команда `grep` и команда `diff` являются утилитами командной строки, которые широко используются в Unix-подобных операционных системах для поиска и сравнения текстовых данных.

Команда `grep`:
- `grep` используется для поиска текста в файле или потоке данных.
- Она принимает на вход строку или регулярное выражение (шаблон) и ищет совпадения в указанном файле или потоке.
- Команда `grep` выводит строки, содержащие совпадения с указанным шаблоном.
- `grep` предлагает различные опции для дополнительной настройки поиска, например, игнорирование регистра, поиск рекурсивно в директориях, вывод номеров строк и другие.

Пример использования команды `grep`:
```shell
grep "pattern" file.txt
```
В этом примере команда `grep` ищет строку, содержащую "pattern", в файле `file.txt`.

Команда `diff`:
- `diff` используется для сравнения содержимого двух файлов или директорий.
- Она анализирует каждую строку или файл и выделяет различия между ними.
- Команда `diff` выводит различия в стандартном формате (разделенные символами '<' и '>'), позволяя видеть изменения между файлами или директориями.
- `diff` предлагает различные опции для управления форматом вывода, игнорирования пробелов, рекурсивного сравнения директорий и другие.

Пример использования команды `diff`:
```shell
diff file1.txt file2.txt
```
В этом примере команда `diff` сравнивает содержимое двух файлов `file1.txt` и `file2.txt` и выводит различия между ними.

Команды `grep` и `diff` являются мощными инструментами для поиска и сравнения текстовых данных, которые используются во многих сценариях разработки, администрирования и анализа данных в Unix-подобных системах.