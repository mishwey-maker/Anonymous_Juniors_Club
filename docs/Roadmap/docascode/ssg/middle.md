## Middle: «Проектирую структуру и настраиваю под задачи»

На Middle-уровне SSG перестаёт быть просто «инструментом для публикации». Теперь это **предмет проектирования**: вы выбираете генератор под задачи команды, настраиваете кастомизацию, интегрируете с CI/CD и обеспечиваете масштабируемость.

**Что входит в Middle-уровень:**

- **Выбор инструмента:** вы понимаете компромиссы между MkDocs (Python, простой Markdown), Docusaurus (React, версионирование, i18n), Sphinx (Python, reStructuredText, мощные cross-references) и Hugo (Go, скорость, Docsy). Вы можете обосновать выбор для конкретного проекта.
- **Продвинутая навигация:** вы проектируете структуру сайта: sidebar, navbar, breadcrumbs, footer. Вы понимаете, как работает автоматическая генерация навигации в MkDocs и ручная — в Docusaurus.
- **Кастомизация:** вы умеете переопределять тему: добавлять кастомные CSS, изменять шаблоны, настраивать цвета и шрифты. В Docusaurus вы работаете с `src/css/custom.css`; в MkDocs — с `extra_css`.
- **Front matter:** вы используете метаданные (title, description, tags, sidebar_position) для управления отображением страниц.
- **Версионирование:** вы настраиваете versioning документации для нескольких версий продукта. Docusaurus поддерживает это «из коробки»; в MkDocs требуется плагин (mike).
- **Интеграция с CI/CD:** вы настраиваете автоматическую сборку и деплой при каждом push в main. Типичный workflow: build → lint → deploy.
- **Поиск:** вы настраиваете полнотекстовый поиск: встроенный (Docusaurus + Algolia) или локальный (MkDocs + search plugin).

*Ключевой принцип Middle: вы **проектируете и настраиваете**. Вы отвечаете за то, чтобы SSG был выбран осознанно, настроен под задачи и интегрирован в процесс.*

---

### Курсы и книги (Middle)

[Docs-as-Code Setup Guide (GitHub)](https://github.com/ann-kilzer/docs-as-code-setup-guide) - Comprehensive guide: выбор инструмента, версионирование, автоматизация, best practices;

[Schulung Docs-as-Code: Technische Dokumentation mit Git, Markdown und CI/CD (GFU)](https://www.gfu.de/schulung/docs-as-code/) - 2-дневный интенсив: Static Site Generators im Vergleich, CI/CD im Einsatz, automatisierte Publishing-Pipelines;

[mike Documentation (GitHub)](https://github.com/jimporter/mike) - Официальная документация mike: управление версиями MkDocs, деплой на GitHub Pages, интеграция с Material for MkDocs;

[Docusaurus Versioning Documentation](https://docusaurus.io/docs/versioning) - Официальная документация по версионированию Docusaurus: `npm run docusaurus docs:version`, работа с `versions.json`;

[MkDocs Material Documentation — Advanced](https://squidfunk.github.io/mkdocs-material/setup/) - Продвинутые разделы: plugins, customization, versioning, search.
