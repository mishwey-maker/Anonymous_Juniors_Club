## Middle: «Проектирую документацию и читаю спецификации»

На Middle-уровне REST/HTTP перестаёт быть просто «языком, который я читаю». Теперь это **предмет анализа**: вы работаете с OpenAPI-спецификациями, проверяете контракты, влияете на качество документации через понимание архитектуры API.

**Что входит в Middle-уровень:**

- **OpenAPI-спецификация:** вы читаете и анализируете OpenAPI 3.0: paths, operations, parameters, requestBody, responses, components, schemas.
- **Валидация контрактов:** вы проверяете, что документация соответствует реальному поведению API. Вы используете schema validation, contract tests, style linting.
- **Аутентификация:** вы документируете OAuth 2.0, API keys, Bearer tokens, basic auth. Вы понимаете, как описать процесс получения токена и его использования в запросах.
- **Пагинация и фильтрация:** вы документируете limit/offset, cursor-based pagination, sorting, filtering.
- **Обработка ошибок:** вы документируете не только коды, но и структуру ошибок (Problem Details, error objects с code, message, details).
- **Rate limiting:** вы документируете ограничения на количество запросов, заголовки (X-RateLimit-Limit, X-RateLimit-Remaining), поведение при превышении.
- **Гибридный подход:** вы понимаете, что автогенерация из OpenAPI покрывает endpoints и параметры, но не даёт контекста. Вы добавляете ручные описания поверх автогенерации.

*Ключевой принцип Middle: вы **анализируете и проверяете** API, а не просто документируете его. Вы отвечаете за точность контракта и полноту документации.*

---

### Курсы и книги (Middle)

[Designing and Documenting APIs with OpenAPI Specification (Coursera)](https://www.coursera.org/learn/designing-documenting-apis-openapi-specification) - Проектирование RESTful API с OpenAPI: endpoints, schemas, versioning strategies, OAuth 2.0, API keys, JWT. Для разработчиков, архитекторов и технических писателей;

[Documenting APIs: OpenAPI Specification (Tom Johnson)](https://idratherbewriting.com/learnapidoc/) - Разделы по OpenAPI 3.0, Swagger UI, testing API docs, publishing API docs. Бесплатный курс для технических писателей;

[OpenAPI Specification 3.0 (swagger.io)](https://swagger.io/specification/) - Официальная спецификация: структура, схемы, примеры;

[API Documentation: Components & Best Practices (Document360)](https://document360.com/blog/api-documentation/) - Разбор компонентов API-документации и лучших практик: base URL, paging, result codes, accuracy, completeness;

[Docs for Developers (Jared Bhatti et al.)](https://link.springer.com/book/10.1007/978-1-4842-7295-1) - Главы об API documentation: research, draft, write, measure.
