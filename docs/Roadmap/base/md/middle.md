[TOC]

## Middle: «Выбираю и настраиваю»

На Middle-уровне Markdown перестаёт быть просто «языком, на котором я пишу». Теперь это предмет решений: какой диалект использовать, какие расширения подключать, какие правила линтинга настроить, как обеспечить единообразие в команде.

Что входит в Middle-уровень:

* **Выбор диалекта:** вы понимаете разницу между CommonMark, GFM, MyST, и можете обосновать, почему для проекта выбран именно этот вариант. Markdown (CommonMark/GFM) — тривиален для изучения, все его знают, он даёт чистые диффы, но имеет ограничения: нет встроенных includes, сносок, сложных таблиц, admonitions.

* **Расширения:** вы знаете, как подключить и использовать admonitions (callouts), footnotes, definition lists, task lists, tabbed code blocks, collapsible sections. Вы понимаете, какие расширения даёт Python-Markdown, какие — MyST, а какие — SSG (MkDocs, Docusaurus).

* **Линтинг и валидация:** вы настраиваете markdownlint для проверки синтаксиса и Vale для проверки стиля. Vale позволяет превратить стайлгайд в исполняемые правила: он ловит жаргон, пассивный залог, несоответствия терминов — прямо в редакторе или в CI.

* **Интеграция с SSG:** вы понимаете, как Markdown-файлы превращаются в сайт через MkDocs, Docusaurus, Sphinx или Hugo. Вы знаете, как работают front matter (YAML-метаданные), навигация, sidebar, версионирование.

* **Стандарты и стайлгайд:** вы можете написать стайлгайд для Markdown: какие заголовки использовать (ATX, не Setext), какую длину строки считать максимальной, когда использовать таблицу, а когда список, как оформлять код и ссылки.

* *Ключевой принцип Middle: вы делаете выбор и объясняете его. Вы не просто «пишете в Markdown», вы отвечаете за то, чтобы команда писала единообразно.*

## Курсы и книги (Middle)

[Docs as Code & Tooling — Middle Level](senior-stack.uz) - подробный разбор выбора языка разметки, SSG, CI-гейтов. Описывает, как принимать решения, а не просто следовать туториалу.

Write Better with Vale (Brian P. Hogan) - единственная книга, целиком посвящённая Vale: как превратить стайлгайд в исполняемые правила, как линтить Markdown, как настроить CI.

[Microsoft Markdown Best Practices](learn.microsoft.com) - реальный корпоративный стайлгайд: ATX-заголовки, лимит строки 100 символов, работа с пробелами и табами.

[Google Markdown Style Guide](https://google.github.io/styleguide/docguide/style.html) - пример строгого, продуманного стайлгайда от Google: простота, консистентность, читаемость исходного текста.

[GitLab Documentation Style Guide](https://docs.gitlab.com/development/documentation/styleguide/) - отличный пример стайлгайда для open-source проекта, написанного на Markdown

[Python-Markdown Extensions](https://python-markdown.github.io/extensions/index.html) - справочник по расширениям: admonitions, footnotes, definition lists, attribute lists