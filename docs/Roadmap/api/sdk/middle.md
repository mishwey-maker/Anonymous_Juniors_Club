## Middle: «Проектирую flow-based справочник и покрываю сценарии»

На Middle-уровне SDK-документация перестаёт быть просто «набором примеров». Теперь это **спроектированная система**, которая ведёт разработчика через реальные сценарии использования. Вы переходите от «документирую методы» к «документирую flows» — последовательности вызовов, которые решают конкретную задачу разработчика.

**Что входит в Middle-уровень:**

- **Flow-based подход:** вы идентифицируете ключевые use cases продукта и группируете сущности SDK (классы, функции) в эти flows. Для каждого flow вы выстраиваете сущности в порядке использования, добавляете «предыдущий» и «следующий» шаг, а также ссылки «See Also».
- **Пользовательский фокус:** вы отвечаете на вопрос «Что я могу построить с этим?», а не «На чём это построено?». Каждый раздел начинается с ответа: для чего это нужно и какую задачу решает.
- **Покрытие сценариев:** вы документируете не только happy path, но и обработку ошибок, edge cases, продвинутые сценарии (batch operations, streaming, pagination).
- **Состояния SDK:** вы документируете SDK across states: Not installed → Installed but not configured → Configured but first use → Active use → Upgrade path.
- **Гибридный подход:** вы понимаете, что автогенерация из docstrings покрывает reference, но не даёт контекста. Вы добавляете ручные описания поверх.
- **Интеграция с CI:** вы настраиваете проверку примеров в CI: синтаксическая проверка, запуск против тестовой среды.
- **Troubleshooting:** вы документируете типичные ошибки SDK и способы их решения.

*Ключевой принцип Middle: вы **проектируете систему**, а не набор разрозненных страниц. Разработчик, читающий SDK-документацию, должен видеть не список методов, а **путь решения задачи**.*

---

### Курсы и книги (Middle)

[SDK Reference Manuals: A flow-based approach (Miguel Caetano)](https://www.slideshare.net/miguelcaetano/sdk-reference-manuals-a-flowbased-approach) - Детальный разбор flow-based подхода: идентификация flows, группировка сущностей, «See Also» ссылки, gotchas. Единственный в своём роде ресурс по SDK-документации для писателей;

[writing-sdk-docs-and-samples Agent Skill (GitHub)](https://github.com/agent-sh/agent-skills/tree/main/writing-sdk-docs-and-samples) - Готовый workflow: scope → map operations → write installation → authentication → operation samples → error handling → troubleshooting;

[Mintlify: SDK Reference Setup](https://mintlify.com/docs/api-playground/sdk-reference) - Как генерировать SDK reference из TypeDoc, DocFX, Javadoc, Sphinx, phpDocumentor;

[liblab CLI](https://github.com/liblab/liblab) - Генерация SDK и SDK-документации из OpenAPI-спецификации;

[Docs for Developers (Jared Bhatti et al.)](https://link.springer.com/book/10.1007/978-1-4842-7295-1) - Главы о code samples, reference documentation, работе с разработчиками.
