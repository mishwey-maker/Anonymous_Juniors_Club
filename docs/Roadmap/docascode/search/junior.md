## Junior: «Понимаю, что документация должна быть находимой»

На Junior-уровне поиск и метаданные — это **осознание того, что документация существует не в вакууме**. Вы учитесь писать заголовки, которые отражают суть страницы, заполнять front matter (title, description) и понимать, как пользователи ищут информацию. Ключевой сдвиг: вы перестаёте думать «я написал текст» и начинаете думать «пользователь найдёт этот текст».

**Что входит в Junior-уровень:**

- **Понимание важности findability:** «Findability precedes usability; you can’t use what you can’t find». Документация, которую не находят, бесполезна.
- **Заголовки и структура:** вы пишете заголовки, которые чётко отражают содержимое страницы. Используйте формулировки, которые вводит пользователь, а не внутренние названия фич. Заголовок H1 должен быть конкретным и описательным.
- **Front matter:** вы понимаете, что такое front matter (YAML-блок в начале Markdown-файла) и умеете заполнять базовые поля: `title`, `description`, `tags`. Mintlify автоматически генерирует мета-теги из frontmatter title и description.
- **Мета-теги для SEO:** вы понимаете, что meta title (50–60 символов) и meta description (150–160 символов) влияют на то, как страница отображается в поисковой выдаче. Они должны быть конкретными, а не шаблонными.
- **Внутренние ссылки:** вы добавляете internal links между связанными страницами. Это помогает и пользователям, и поисковым краулерам.
- **Понимание, как работает поиск в SSG:** вы знаете, что в MkDocs есть встроенный search plugin (работает на lunr), а в Docusaurus — интеграция с Algolia DocSearch.

*Ключевой принцип Junior: вы **следуете** правилам оформления заголовков и метаданных. Если в проекте принято заполнять `description` для каждой страницы — вы делаете именно так.*

---

### Курсы и книги (Junior)

[How to use SEO techniques to improve your documentation (GitBook)](https://www.gitbook.com/blog/seo-techniques-for-documentation) - Практическое руководство: keywords, headings, metadata, internal links. Quick takeaways для старта;

[SEO metadata (Progress Telerik Style Guide)](https://docs.telerik.com/devtools/wpf/styling-and-appearance/style-guide/seo-metadata) - Пример реализации meta block: title, description, tags. Правила заполнения;

[Writing documentation so search can find it (Ansible)](https://docs.ansible.com/ansible/latest/community/documentation_contribs.html) - Практические советы: clear headings, numbered lists, первые предложения описывают тему страницы;

[MkDocs Search Plugin](https://www.mkdocs.org/user-guide/configuration/#search) - Официальная документация: как работает встроенный поиск, как настроить язык;

[Docusaurus Search](https://docusaurus.io/docs/search) - Официальная документация: как подключить Algolia DocSearch, какие поля заполнять.
