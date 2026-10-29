## Senior: «Определяю стандарт и управляю lifecycle»

На Senior-уровне OpenAPI становится **элементом архитектуры документации**. Вы не просто создаёте спецификации, вы **управляете их lifecycle**: версионирование, breaking changes, автоматизация, стандартизация, обучение команд.

**Что входит в Senior-уровень:**

- **Стратегия spec-driven документации:** вы определяете, как OpenAPI вписывается в общую стратегию: единый источник истины для документации, тестов, SDK, кода.
- **Governance:** вы определяете политику: кто отвечает за актуальность спецификации, как проверяется соответствие коду, как обрабатываются breaking changes.
- **Версионирование:** вы управляете версиями спецификации: как поддерживать несколько версий API, как архивировать старые версии, как коммуницировать изменения.
- **CI/CD для OpenAPI:** вы настраиваете пайплайн: валидация → генерация → публикация. Вы используете CI-гейты для проверки свежести спецификации и примеров.
- **Автоматизация:** вы настраиваете генерацию документации из спецификации, генерацию SDK, генерацию тестов.
- **Масштабирование:** вы проектируете систему, которая выдерживает рост: добавление новых API, версий, языков без ручной работы.
- **Обучение:** вы обучаете команды работе с OpenAPI, проводите воркшопы, создаёте внутренние стандарты.

*Ключевой принцип Senior: вы **определяете правила игры** и **отвечаете за их соблюдение в масштабе**. Инженеры приходят к вам за советом по API-дизайну **до** начала разработки.*

---

### Курсы и книги (Senior)

[Designing APIs with Swagger and OpenAPI (Josh Ponelat, Lukas Rosenstock, продвинутые главы)](https://www.manning.com/books/designing-apis-with-swagger-and-openapi) - Главы о versioning, breaking changes, codegen, работе с кросс-функциональными командами;

[The Design of Web APIs, Second Edition (Arnaud Lauret, продвинутые главы)](https://www.manning.com/books/the-design-of-web-apis-second-edition) - Продвинутые главы: стандартизация API-дизайна, automation, rationale;

[Specialization in API Documentation (UW Professional & Continuing Education)](https://www.pce.uw.edu/specializations/api-documentation) - Программа для технических писателей: API fundamentals, OpenAPI, docs-as-code, testing;

[Docs for Developers (Jared Bhatti et al.)](https://link.springer.com/book/10.1007/978-1-4842-7295-1) - Стратегия документации, архитектура, масштабирование, обучение команды;

[GitBook: Integrating with CI/CD](https://docs.gitbook.com/integrations/git-sync) - Как автоматизировать обновление OpenAPI-спецификации через GitBook CLI.
