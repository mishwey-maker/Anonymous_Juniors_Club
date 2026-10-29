## Middle: «Проектирую структуру и связываю с системой»

На Middle-уровне вы перестаёте писать reference «по шаблону» и начинаете **проектировать** справочную систему. Архитектура reference должна отражать архитектуру описываемой системы.

**Что входит в Middle-уровень:**

- **Архитектура reference:** вы проектируете структуру справочника так, чтобы читатель мог найти нужный факт за минимальное время. Группировка по ресурсам (endpoints, параметры, коды ошибок) или по модулям.
- **Связывание с системой:** reference для API должен генерироваться из единого источника истины — OpenAPI-спецификации. Вы понимаете, как работает schema-based generation.
- **Гибридный подход:** автоматическая генерация покрывает endpoints и параметры, но не даёт контекста. Вы добавляете ручные описания поверх автогенерации.
- **Валидация:** вы проверяете reference на точность: соответствует ли описание реальному поведению API? Вы тестируете примеры.
- **Метрики:** вы измеряете эффективность reference: как часто его ищут, находят ли нужное, сколько времени тратят.

*Ключевой принцип Middle: вы **проектируете структуру reference** и связываете её с системой через OpenAPI.*

---

### Курсы и книги (Middle)

[Should you generate docs from your API schema? (Mintlify)](https://mintlify.com/blog/generate-docs-from-schema) - Детальный разбор гибридного подхода: автогенерация + ручные описания, ограничения schema-based generation;

[How to write incredible API documentation (GitBook)](https://www.gitbook.com/blog/how-to-write-api-documentation) - Организация endpoints: группировка по ресурсам или workflow, избегание длинных плоских списков;

[Create API Documentation (Microsoft Learn)](https://learn.microsoft.com/en-us/training/modules/create-api-documentation/) - Выбор формата (OpenAPI или Markdown), примеры, обновление при изменениях, обратная связь от пользователей;

[Using OpenAPI for API Documentation (API7.ai)](https://api7.ai/blog/openapi-api-documentation) - Валидация спецификации и реализации: syntax validation, style linting, contract tests;

[Diátaxis Framework — Applying Diátaxis](https://diataxis.fr/) - Продвинутое применение: как связывать reference с другими типами документации.
