## Middle: «Настраиваю тесты и автоматизирую проверки»

На Middle-уровне Postman перестаёт быть просто «инструментом проверки». Теперь это **среда для автоматизации**: вы пишете тесты, настраиваете переменные, интегрируете проверки в CI/CD. Вы отвечаете за то, чтобы документация была не только точной, но и **постоянно проверяемой**.

**Что входит в Middle-уровень:**

- **Написание тестов:** вы пишете assertions в Postman: проверка статус-кода, проверка полей в ответе, проверка времени ответа. Вы используете JavaScript-сниппеты.
- **Переменные и environments:** вы настраиваете environment variables для разных сред (dev, staging, prod). Вы используете collection variables для общих значений.
- **Pre-request scripts:** вы пишете скрипты, которые выполняются до запроса: генерация токена, установка timestamp, подготовка данных.
- **Collection Runner:** вы запускаете всю коллекцию запросов, проверяете результаты, экспортируете отчёты.
- **Автоматизация с Newman:** вы устанавливаете Newman (CLI для Postman) и запускаете коллекции из командной строки. Вы интегрируете Newman в CI/CD.
- **Тестирование ошибок:** вы проверяете не только успешные сценарии, но и обработку ошибок: 400, 401, 403, 404, 500.
- **Гибридный подход:** вы используете Postman для проверки документации, сгенерированной из OpenAPI.

*Ключевой принцип Middle: вы **автоматизируете** проверки и **интегрируете** их в процесс. Документация проверяется при каждом изменении API.*

---

### Курсы и книги (Middle)

[API Testing and Development with Postman (IEEE)](https://iln.ieee.org/courses/api-testing-and-development-with-postman) - Comprehensive introduction to API testing and development using Postman: terminology, types, best practices for designing and documenting APIs, security and performance testing;

[API Testing with Postman: From Beginner to Advanced (Udemy)](https://www.udemy.com/course/api-testing-with-postman/) - 7+ часов: от первого запроса до автоматизации с Newman, data-driven testing (CSV/JSON), CI/CD интеграция;

[Mastering Postman (Dave Westerveld)](https://www.oreilly.com/library/view/mastering-postman/9781838987562/) - Комплексное руководство: API design, testing, documentation, mocking. Покрывает Postman CLI для продвинутого тестирования и автоматизации;

[Postman Docs: Collection Runner & Newman](https://learning.postman.com/docs/collections/running-collections/intro-to-collection-runs/) - Официальная документация: как запускать коллекции, настраивать iterations, экспортировать отчёты;

[Postman Docs: Writing Tests](https://learning.postman.com/docs/writing-scripts/test-scripts/) - Официальное руководство по написанию тестов: assertions, snippets, работа с JSON.
