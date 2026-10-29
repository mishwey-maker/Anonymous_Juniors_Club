## Junior: «Запускаю и публикую по инструкции»

На Junior-уровне SSG — это **инструмент для публикации**. Вы учитесь запускать готовый генератор локально, разбираться в его базовой структуре и публиковать документацию в интернет. Ключевой сдвиг: вы перестаёте думать о документации как о наборе файлов в папке и начинаете видеть в ней **сайт**, который можно собирать и деплоить.

**Что входит в Junior-уровень:**

- **Понимание принципа работы SSG:** вы знаете, что SSG берёт контент (Markdown, reStructuredText, AsciiDoc), применяет тему и создаёт статические HTML-страницы для публикации.
- **Установка и запуск:** вы можете установить MkDocs или Docusaurus на локальную машину, запустить dev-сервер и увидеть свой сайт в браузере. Для MkDocs типичный запуск — `mkdocs serve`; для Docusaurus — `npm run start`.
- **Базовая структура проекта:** вы понимаете, где лежат контентные файлы (`docs/`), где конфигурация (`mkdocs.yml` или `docusaurus.config.js`), и как они связаны.
- **Навигация:** вы умеете добавлять новые страницы и настраивать их в боковом меню. В MkDocs навигация задаётся в `mkdocs.yml` в разделе `nav`; в Docusaurus — через `sidebars.js`.
- **Публикация:** вы умеете собрать сайт (`mkdocs build` или `npm run build`) и опубликовать его на GitHub Pages. Это первый шаг к тому, чтобы ваша документация стала доступна пользователям.

*Ключевой принцип Junior: вы **запускаете и публикуете**, используя готовые инструкции и шаблоны. Если что-то не работает — вы ищете решение в документации инструмента.*

---

### Курсы и книги (Junior)

[MkDocs Documentation](https://www.mkdocs.org/) - Официальная документация MkDocs: от установки до кастомизации. Разделы «Getting Started» и «User Guide» — обязательны для старта;

[Docusaurus Documentation](https://docusaurus.io/docs) - Официальная документация Docusaurus: от установки до версионирования. Раздел «Getting Started» даёт быстрый старт;

[Publish your website with Docusaurus (Tech Writer's Tribe)](https://techwriterstribe.com/courses/publish-your-website-with-docusaurus/) - Курс **специально для технических писателей**, не требует опыта программирования. 4 сессии по 3 часа: Markdown, Git, Docusaurus, GitHub Actions, автоматическая публикация;

[Material for MkDocs Documentation](https://squidfunk.github.io/mkdocs-material/) - Официальная документация темы Material for MkDocs: настройка, кастомизация, плагины. Один из самых популярных вариантов оформления для MkDocs;

[Further Website Development for Software Projects (Imperial College London)](https://www.coursera.org/learn/website-development-for-software-projects) - Курс о static site generation и GitHub Pages: настройка SSG, добавление навигации, деплой.
