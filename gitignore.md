[< к содержанию](./readme.md)

# Файл исключений .gitignore
Команда `git add` производит добавление всех файлов всех в отслеживаемые, однако некоторые данные отслеживать не требуется для этого они помещаются в файл с расширением `.gitignore`

Файл `.gitignore` представляет собой текстовый файл с перечнем шаблонов  файловых имён, которые не должны отслеживаться. 

**Основные правила синтаксиса такого файла**

1. Одна строчка - один шаблон;
2. Пустые строки игнорируются;
3. Чтобы написать комментарий, вначале строки укажите знак `#`;
4. Символ `/` вначале строки указывает, что правило применяется только к файлам и каталогам , которые распологаются в том же каталоге, что и сам файл `.gitignore`;
5. Доступно использования спецсимволов. 

| Спецсимвол    | Расшифровка |
| :-------------: | ------------- |
| `*`           |Заменяет любое количество символов (в том числе ноль)|
| `?`           |Заменяет любой 1 символ |
| `**`          |Используется для указания любого кол-ва подкаталогов |
| `!`           |Означает инвертирование правила (Кроме) |
| `/`           |Экранирует спец. символ  |
| `\`           |Разделяет уровни каталогов |