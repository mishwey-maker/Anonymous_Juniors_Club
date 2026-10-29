## Junior: «Понимаю пайплайн и запускаю готовый workflow»

На Junior-уровне CI/CD — это **процесс, за которым вы наблюдаете и в котором участвуете**. Вы учитесь работать с pull requests, понимать статусы проверок и исправлять ошибки, которые находит автоматика. Ключевой сдвиг: вы перестаёте воспринимать документацию как отдельный артефакт и начинаете видеть в ней **часть инженерного workflow** — от коммита до публикации.

**Что входит в Junior-уровень:**

- **Понимание принципа docs-as-code:** документация живёт в том же репозитории, что и код, использует те же инструменты (Git, Markdown, pull requests) и проходит те же этапы проверки.
- **Работа с pull requests:** вы создаёте PR, видите, какие проверки запустились, и понимаете, что означает красный или зелёный статус. В современных workflow CI-система запускает тесты документации при каждом PR.
- **Базовые проверки:** вы знаете, что CI проверяет: сборка сайта (build), проверка ссылок (broken links), линтинг (стиль, форматирование), орфография. Вы умеете читать логи ошибок и исправлять их.
- **Простые workflow GitHub Actions:** вы понимаете структуру YAML-файла: `name`, `on`, `jobs`, `steps`. Вы можете прочитать существующий workflow и понять, что он делает.
- **Деплой:** вы знаете, что после merge в main документация публикуется автоматически. Вы понимаете, что такое GitHub Pages или Read the Docs как платформа для публикации.

*Ключевой принцип Junior: вы **участвуете** в CI/CD-процессе, а не проектируете его. Если проверка упала — вы исправляете ошибку и делаете новый коммит.*

---

### Курсы и книги (Junior)

[How to Set Up Documentation as Code with Docusaurus and GitHub Actions (freeCodeCamp)](https://www.freecodecamp.org/news/set-up-documentation-as-code-with-docusaurus-and-github-actions/) - Пошаговый гайд **специально для технических писателей**: создание docs-сайта, настройка GitHub Actions для проверки грамматики через Vale перед merge. Beginner-friendly;

[Publish your website with Docusaurus (Tech Writer's Tribe)](https://techwriterstribe.com/courses/publish-your-website-with-docusaurus/) - 4 сессии: Markdown, Git, Docusaurus, GitHub Actions, автоматическая публикация. **Не требует опыта программирования**;

[Schulung Docs-as-Code: Technische Dokumentation mit Git, Markdown und CI/CD (GFU)](https://www.gfu.de/schulung/docs-as-code/) - 2-дневный интенсив: CI/CD-Pipelines, Build-Prozesse, Testing (broken links, linting), Deployment;

[Docs as Code (techwriters.ru)](https://techwriters.ru/docs-as-code/) - Подробное описание процесса docs-as-code на русском: схема workflow, CI/CD Pipeline, инструменты;

[GitHub Actions Documentation](https://docs.github.com/en/actions) - Официальная документация GitHub Actions: от первых шагов до продвинутых сценариев.
