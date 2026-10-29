## Middle: «Настраиваю поиск и управляю метаданными»

На Middle-уровне поиск и метаданные перестают быть просто «оформлением». Теперь это **предмет настройки**: вы выбираете поисковый движок, настраиваете метаданные для команды, управляете таксономией и обеспечиваете, чтобы документация была находимой.

**Что входит в Middle-уровень:**

- **Настройка поиска:** вы настраиваете поисковый движок для документационного сайта. Варианты: встроенный search plugin в MkDocs (client-side, lunr), Algolia DocSearch (hosted, для open-source бесплатно), Redocly Realm. Вы понимаете компромиссы: client-side проще, hosted — мощнее.
- **Настройка Algolia DocSearch:** вы подаёте заявку на DocSearch (бесплатно для open-source), настраиваете crawler, добавляете `algolia` field в `docusaurus.config.js`. Вы понимаете, как работает индексация.
- **Управление метаданными:** вы создаёте стандарт заполнения front matter для команды: какие поля обязательны (`title`, `description`), какие опциональны (`tags`, `owner`, `version`). Вы используете metadata для маршрутизации контента, фильтрации и поиска.
- **Таксономия:** вы создаёте таксономию — систему категорий и тегов для классификации контента. Вы понимаете, что такое metadata, taxonomy и classification. Вы используете теги для группировки связанного контента.
- **Настройка индексации:** вы настраиваете, какие страницы индексируются, какие исключаются (например, draft, internal pages). Вы понимаете, как работает `sitemap.xml` и robots.txt.
- **Поисковая аналитика:** вы анализируете поисковые запросы пользователей: что ищут, что находят, что не находят. Вы используете эти данные для улучшения документации.
- **Внутренняя поисковая оптимизация:** вы настраиваете вес страниц в поиске (page ranking factor в Mintlify: значения >1 приоритезируют, 0–1 де-приоритезируют).

*Ключевой принцип Middle: вы **настраиваете и управляете**. Вы отвечаете за то, чтобы пользователи находили нужное, а метаданные помогали в управлении контентом.*

---

### Курсы и книги (Middle)

[UX and Information Architecture Basics for Technical Writers (Udemy)](https://www.udemy.com/course/ux-and-information-architecture-basics-for-technical-writers/) - Learn 3 taxonomy development and 2 card sorting techniques. Understand what is metadata, taxonomy and classification;

[SEO techniques for documentation (GitBook, полная версия)](https://www.gitbook.com/blog/seo-techniques-for-documentation) - Keyword research, headings, metadata, internal links, indexing, accessibility;

[Tune search and SEO (Redocly)](https://redocly.com/docs/realm/search/) - Choose a search engine, add facets, exclude content from index. Set metadata, sitemaps;

[Algolia DocSearch Documentation](https://docsearch.algolia.com/docs/what-is-docsearch) - Официальная документация: getting started, configuration, crawler setup;

[MkDocs Search Plugin (продвинутые разделы)](https://squidfunk.github.io/mkdocs-material/setup/setting-up-site-search/) - Настройка языков, конфигурация, интеграция с Material for MkDocs.
