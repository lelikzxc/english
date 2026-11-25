# English

Меню для локальных интерактивных пробников TOEFL iBT®. Открой `TOEFL/index.html` в браузере после добавления своих HTML-вариантов.

## Как добавить варианты

1. Скачай или клонируй репозиторий в папку `english`.
2. Положи готовый HTML-вариант в нужную папку по схеме ниже. Если у тебя есть `source.pdf` для этого варианта, оставь его рядом с `test.html`, чтобы работала ссылка на исходный билет.
3. Открой `english/TOEFL/index.html` и выбери добавленный вариант. В готовых HTML-файлах аудио уже встроено.

```text
english/
└── TOEFL/
    ├── index.html
    ├── variants/
    │   ├── student-01/test.html
    │   ├── student-02/test.html
    │   ├── teacher-01/test.html
    │   ├── teacher-03/test.html
    │   ├── teacher-04/test.html
    │   └── teacher-05/test.html
    ├── toefl-teacher-02.html
    └── teacher-02/
        └── toefl-ibt-teachers-resources-practice-test-2.pdf
```

Teacher Practice Test 2 использует отдельный путь, указанный внизу схемы. Сохрани имена файлов и папок, чтобы ссылки меню и кнопка «Все варианты» работали.

Отдельные PDF и записи можно скачать на [официальной странице ETS](https://www.ets.org/toefl/teachers-advisors-agents/ibt/teaching/preparing-students.html). Для открытия из меню нужен уже подготовленный интерактивный HTML.

## Что остаётся на устройстве

Храни готовые варианты, оригинальные PDF, аудио, результаты и записи ответов локально. `.gitignore` позволяет обычному `git add` добавлять только этот README, сам `.gitignore` и `TOEFL/index.html`. Перед пушем список файлов можно проверить командой `git diff --cached --name-only`.

TOEFL и TOEFL iBT — товарные знаки ETS. Материалы ETS используются согласно условиям правообладателя. [Правила лицензирования ETS](https://www.ets.org/legal/permissions/licensing.html)
