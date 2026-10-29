## Junior: «Знаю структуру и пишу по шаблону»

На Junior-уровне вы учитесь **распознавать** reference и писать его по готовому шаблону. Ключевой сдвиг: вы перестаёте «объяснять» в справочнике и начинаете **каталогизировать факты**.

**Что входит в Junior-уровень:**

- **Понимание сути reference:** это полный каталог фактов о чём-либо: API endpoints, параметры, настройки, коды ошибок, глоссарий.
- **Структура reference:** каждый элемент (функция, параметр, команда) следует одному и тому же паттерну: Name → Type → Description → Parameters (таблица: Name, Type, Default, Description) → Returns → Examples → Notes.
- **Таблицы и списки:** reference должен быть сканируемым. Параметры описываются в таблицах, а не в прозе.
- **Точность:** информация должна быть проверена по реальной системе. Reference не может быть «примерно верным».
- **Отсутствие редактуры:** никаких оценочных суждений («эта опция лучше»), никаких tutorial-объяснений. Только факты.
- **Примеры:** минимально полезный пример для каждого элемента — как вызвать функцию, как выглядит ответ.

*Ключевой принцип Junior: вы **пишете reference по шаблону**, не добавляя редактуры и оценочных суждений.*

---

### Курсы и книги (Junior)

[Diátaxis Framework — Reference](https://diataxis.fr/reference/) - Официальное описание reference: техническое описание фактов, нейтральность, структура, отражающая архитектуру системы;

[Doc Types Guide (GitHub)](https://github.com/ann-kilzer/doc-types-guide) - Шаблон reference с примером: Name → Type → Description → Parameters → Returns → Examples → Notes;

[Google Technical Writing One](https://developers.google.com/tech-writing/one) - База: аудитория, структура, точность. Разделы о таблицах и списках применимы к reference;

[Write effective documentation (Home Office)](https://engineering.homeoffice.gov.uk/patterns/documentation/) - Разделение контента на conceptual, task-based и reference; рекомендации по структуре;

[GitLab Technical Writing Fundamentals](https://about.gitlab.com/handbook/product/ux/technical-writing/fundamentals/) - Типы топиков, включая reference; грамматика и стилевые требования.
