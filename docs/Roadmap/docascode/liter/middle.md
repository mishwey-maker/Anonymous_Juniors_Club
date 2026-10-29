## Middle: «Настраиваю линтеры и автоматизирую проверки»

На Middle-уровне линтеры перестают быть просто «инструментами, которые находят ошибки». Теперь это **предмет настройки**: вы выбираете правила, создаёте кастомные конфигурации, интегрируете линтеры в CI/CD и обеспечиваете, чтобы команда работала по единым стандартам.

**Что входит в Middle-уровень:**

- **Настройка markdownlint:** вы создаёте `.markdownlint.yaml` с правилами, адаптированными под проект. Вы понимаете, какие правила можно отключить: MD013 (длина строки) часто отключается для таблиц и длинных URL, MD024 (дублирующиеся заголовки) — для changelog. Вы настраиваете `markdownlint-cli2` для проверки конкретных папок.
- **Настройка Vale:** вы создаёте `.vale.ini` с указанием стилей. Вы подключаете готовые стили (Google, Microsoft, write-good, proselint) и создаёте кастомные правила. Пример кастомного правила: запрет на «simply», «just», «obviously», «easy» — слова, которые создают предположение о лёгкости задачи.
- **Настройка cspell:** вы создаёте `cspell.json` с кастомным словарём для технических терминов, названий продуктов, аббревиатур. Вы понимаете, как игнорировать определённые пути и типы файлов.
- **Настройка проверки ссылок:** вы выбираете инструмент: `lychee`, `linkinator`, `markdown-link-check`, `mlc`. Вы настраиваете конфигурацию: таймауты, повторные попытки, игнорирование определённых доменов.
- **Интеграция в CI/CD:** вы настраиваете GitHub Actions (или GitLab CI) так, чтобы все проверки запускались при каждом PR: markdownlint → Vale → cspell → link check → build. Если любая проверка падает — PR не может быть смержен.
- **Pre-commit hooks:** вы настраиваете pre-commit для всей команды, чтобы линтеры запускались локально перед коммитом. Это снижает количество «красных» CI-сборок.
- **Управление правилами:** вы определяете, какие правила обязательны (error), какие — рекомендательны (warning), какие — отключены. Вы документируете это в стайлгайде.

*Ключевой принцип Middle: вы **настраиваете и автоматизируете**. Вы отвечаете за то, чтобы линтеры были настроены под проект и помогали команде, а не мешали.*

---

### Курсы и книги (Middle)

[Write Better with Vale (Brian P. Hogan)](https://books.google.com/books/about/Write_Better_with_Vale.html?id=nMabEQAAQBAJ) - Единственная книга, целиком посвящённая Vale: как превратить стайлгайд в исполняемые правила, как настраивать `.vale.ini`, как интегрировать в CI. Использует Vale 3.12.0+;

[Scaling Writing Practices with Vale.sh (Spectro Cloud)](https://www.spectrocloud.com/blog/scaling-writing-practices-with-vale-sh) - Реальный кейс: как команда внедрила Vale, какие правила создала, как масштабировала. Пример кастомного правила против «simply»;

[Elastic vale-rules (GitHub)](https://github.com/elastic/vale-rules) - Готовый набор правил Vale от Elastic: примеры кастомных правил, настройка per-repo overrides, интеграция с GitHub Actions;

[markdownlint Configuration (GitHub)](https://github.com/DavidAnson/markdownlint/blob/main/doc/Configuration.md) - Примеры `.markdownlint.yaml` для документационных проектов: адаптация правил под реальные задачи;

[Documentation Lifecycle Management Guide (GitHub)](https://github.com/ann-kilzer/documentation-lifecycle-guide) - Полный workflow: Write → Lint → Review → Publish → Audit. Включает pre-commit hooks и CI-интеграцию.
