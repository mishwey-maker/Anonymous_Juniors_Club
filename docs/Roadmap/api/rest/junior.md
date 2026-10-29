## Junior: «Читаю API и документирую по шаблону»

На Junior-уровне REST/HTTP — это **язык, на котором говорит API**. Вы учитесь читать спецификации, понимать запросы и ответы, различать методы и коды. Ключевой сдвиг: вы перестаёте «пересказывать» API и начинаете **документировать его контракт** — что можно сделать, какие данные передать, что вернётся в ответ.

**Что входит в Junior-уровень:**

- **HTTP-методы:** вы понимаете разницу между GET (чтение, безопасный, идемпотентный), POST (создание, не идемпотентный), PUT (полная замена, идемпотентный), PATCH (частичное обновление), DELETE (удаление, идемпотентный).
- **Статус-коды:** вы различаете пять семейств: 1xx (информационные), 2xx (успех), 3xx (редиректы), 4xx (ошибки клиента), 5xx (ошибки сервера). Вы документируете как минимум один успешный код (200, 201, 204) и типичные ошибки (400, 401, 404, 500).
- **URL-структура:** вы понимаете компоненты: scheme (https), host (api.example.com), path (/users/123), query parameters (?page=1&limit=20), fragment (#section).
- **Заголовки:** вы понимаете Content-Type (application/json), Accept, Authorization (Bearer token), Location (в ответе 201).
- **Структура документации эндпоинта:** вы документируете по шаблону: Resource description → Endpoint and method → Parameters (path, query, body) → Sample request → Sample response → Status codes → Error codes → Code samples.
- **JSON:** вы читаете JSON, понимаете вложенность объектов и массивов, различаете типы данных (string, number, boolean, array, object, null).

*Ключевой принцип Junior: вы **читаете и документируете** API, а не проектируете его. Если метод неверный — вы документируете то, что есть, и уточняете у разработчика.*

---

### Курсы и книги (Junior)

[Documenting APIs: Introduction to REST APIs (Tom Johnson)](https://idratherbewriting.com/learnapidoc/docapis_introtoapis.html) - Бесплатный курс для технических писателей: контекстуализирует REST через реальный weather API, учит endpoints, parameters, curl, JSON, статус-коды. Более 900 страниц, 17 глав;

[Learn API Technical Writing 2: REST for Writers (Udemy)](https://www.udemy.com/course/learn-api-technical-writing-2-rest-for-writers/) - Курс **специально для технических писателей**: без опыта программирования. Учит документировать REST-запросы и ответы;

[HTTP Editorial Style Guide (httpwg.org)](https://httpwg.org/http-extensions/draft-ietf-httpbis-semantics.html) - Официальное руководство по написанию HTTP: как правильно упоминать методы, статус-коды, заголовки. Методы — без кавычек, статус-коды — число + фраза в скобках;

[HTTP Status Codes Reference (MDN Web Docs)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) - Полный справочник статус-кодов с описанием и примерами использования;

[Learn API Documentation with JSON and XML (Peter Gruenbaum, Class Central)](https://www.classcentral.com/course/udemy-learn-api-technical-writing-json-and-19418) - Курс для технических писателей: чтение и документирование структурированных данных в JSON и XML.
