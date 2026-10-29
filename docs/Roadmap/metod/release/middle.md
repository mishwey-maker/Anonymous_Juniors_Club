## Middle: «Проектирую процесс и связываю с релизным циклом»

На Middle-уровне вы перестаёте писать отдельные release notes «по запросу» и начинаете **проектировать процесс**.

**Что входит в Middle-уровень:**

- **Процесс сбора:** вы выстраиваете workflow, при котором changelog-фрагменты создаются **в момент PR**, а не восстанавливаются постфактум. Инструменты: Changesets, Changie, conventional commits.
- **Связывание с документацией:** release notes должны ссылаться на обновлённые how-to, reference и migration guides.
- **Адаптация под аудиторию:** вы пишете отдельные версии release notes для разных аудиторий: end users, admins, developers, integrators.
- **Semantic Versioning:** вы понимаете, как категории изменений соотносятся с SemVer (patch, minor, major).
- **Валидация:** вы проверяете, что release notes точны: соответствует ли описание реальному поведению?
- **Метрики:** вы измеряете эффективность release notes: open rates, click-through, support tickets после релиза.

*Ключевой принцип Middle: вы **проектируете процесс сбора и публикации** release notes.*

---

### Курсы и книги (Middle)

[How to write release notes (Mintlify, разделы о workflow)](https://mintlify.com/blog/how-to-write-release-notes) - Разделы о повторяемом процессе написания и поддержании точности changelog в shipping workflow;

[Changelog Standards (Universal Dev Standards)](https://github.com/universal-dev-standards/changelog-standards) - Стандарт для CHANGELOG.md: user-centric, consistent, complete, timely;

[Keep a Changelog — Automation](https://keepachangelog.com/en/1.0.0/) - Разделы о Semantic Versioning и автоматизации;

[Docs for Developers (Jared Bhatti et al.)](https://link.springer.com/book/10.1007/978-1-4842-7295-1) - Глава о release notes: research, draft, write different kinds of documentation;

[Semantic Versioning](https://semver.org/) - Официальная спецификация SemVer: patch, minor, major.
