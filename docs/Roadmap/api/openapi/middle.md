## Middle: «Пишу спецификацию и настраиваю генерацию»

На Middle-уровне OpenAPI перестаёт быть просто «форматом, который я читаю». Теперь это **инструмент проектирования и автоматизации**. Вы создаёте спецификации с нуля, настраиваете генерацию документации, интегрируете OpenAPI в docs-as-code.

**Что входит в Middle-уровень:**

- **Написание спецификации с нуля:** вы создаёте OpenAPI 3.0/3.1 документ для нового API: paths, operations, parameters, requestBody, responses, components/schemas.
- **Переиспользование компонентов:** вы понимаете, как работает `components`: reusable schemas, parameters, responses, securitySchemes. Вы избегаете дублирования через `$ref`.
- **Безопасность:** вы документируете securitySchemes: OAuth 2.0, API keys, Bearer tokens, basic auth.
- **Генерация документации:** вы настраиваете Swagger UI или Redoc для отображения спецификации. Вы понимаете разницу: Swagger UI — интерактивный, с «Try it out»; Redoc — read-focused, более чистый и современный.
- **Интеграция в docs-as-code:** вы понимаете, как OpenAPI-файл живёт в Git-репозитории рядом с Markdown-документацией. Вы настраиваете CI для валидации спецификации и генерации документации.
- **Валидация и линтинг:** вы настраиваете проверку спецификации в CI: syntax validation, style linting, проверка на breaking changes.
- **Гибридный подход:** вы понимаете, что автогенерация из OpenAPI покрывает reference, но не даёт контекста. Вы добавляете ручные описания поверх.

*Ключевой принцип Middle: вы **создаёте и автоматизируете**. Вы отвечаете за то, чтобы спецификация была точной, полной и генерировала качественную документацию.*

---

### Курсы и книги (Middle)

[Designing APIs with Swagger and OpenAPI (Josh Ponelat, Lukas Rosenstock)](https://www.manning.com/books/designing-apis-with-swagger-and-openapi) - Комплексное руководство: от концепции до продакшена. Реальные проекты, OpenAPI syntax, codegen, versioning, breaking changes;

[The Design of Web APIs, Second Edition (Arnaud Lauret)](https://www.manning.com/books/the-design-of-web-apis-second-edition) - Обновлённое издание: покрывает последние изменения OpenAPI, документирование REST API с OpenAPI и JSON Schema;

[OpenAPI 3.1 API Design Course (CodeRed)](https://codered.eccouncil.org/course/openapi-3-1-api-design) - Для разработчиков, архитекторов и **технических писателей**: design-first подход, создание OpenAPI-документа, paths, operations, reusable components;

[Specialization in API Documentation (UW Professional & Continuing Education)](https://www.pce.uw.edu/specializations/api-documentation) - 11-недельная программа для технических писателей: API fundamentals, OpenAPI, docs-as-code, testing;

[GitHub: Best Practices (Spec Authoring)](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.1.0.md) - Правила написания спецификаций: operationId, reuse components, clear responses.
