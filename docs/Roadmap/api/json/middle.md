## Middle: «Проектирую схемы и проверяю валидность»

На Middle-уровне JSON/XML перестаёт быть просто «форматом, который я читаю». Теперь это **предмет анализа**: вы работаете со схемами (JSON Schema, XSD), проверяете валидность данных, обеспечиваете консистентность документации с реальным API.

**Что входит в Middle-уровень:**

- **JSON Schema:** вы читаете и анализируете JSON Schema: type, properties, required, enum, format, items, additionalProperties. Вы понимаете, как схема описывает контракт данных и как использовать её для валидации.
- **XSD (XML Schema Definition):** вы читаете XSD: elements, attributes, types, restrictions, complexType. Вы понимаете, как XSD описывает структуру XML-документа и как валидировать XML по схеме.
- **Валидация данных:** вы используете JSON Schema и XSD для проверки: соответствует ли реальный ответ API описанной схеме?
- **Связь с OpenAPI:** вы понимаете, как JSON Schema используется внутри OpenAPI 3.0 для описания requestBody и responses.
- **Документирование ошибок:** вы описываете структуру ошибок в JSON/XML: код, сообщение, детали.
- **Гибридный подход:** вы понимаете, что автогенерация из схем покрывает структуры, но не даёт контекста. Вы добавляете ручные описания поверх.
- **Инструменты:** вы работаете с инструментами валидации: JSON Schema Validator, oXygen для XML, Swagger для OpenAPI.

*Ключевой принцип Middle: вы **анализируете и проверяете** структуры данных, а не просто документируете их. Вы отвечаете за точность контракта и полноту документации.*

---

### Курсы и книги (Middle)

[JSON Schema Documentation (json-schema.org)](https://json-schema.org/) - Официальная документация JSON Schema: type, properties, required, enum, format, validation keywords;

[XSD Tutorial (W3Schools)](https://www.w3schools.com/xml/schema_intro.asp) - Основы XSD: elements, attributes, types, restrictions, complexType;

[Pro RESTful APIs (Sanjay Patni)](https://link.springer.com/book/10.1007/978-1-4842-2764-0) - Глава 3 «Introduction — XML, JSON»: дизайн, построение и интеграция с REST, JSON, XML;

[Understanding JSON Schema (json-schema.org)](https://json-schema.org/understanding-json-schema/) - Продвинутое руководство: schema composition, conditional validation, references;

[API Technical Writing: JSON and XML (Consult-Timmins)](https://www.consult-timmins.com/api-technical-writing-json-xml/) - Module 2: JSON syntax, structure, nested objects; Module 4: Hands-on writing API requests/responses in JSON; Module 7: Documenting API errors.
