# CI/CD для документации — Middle

## Middle: «Настраиваю пайплайн и автоматизирую проверки»

На Middle-уровне CI/CD перестаёт быть просто «процессом, в котором я участвую». Теперь это **предмет проектирования**: вы настраиваете workflow с нуля, выбираете инструменты, автоматизируете проверки и обеспечиваете, чтобы документация была качественной до попадания к пользователю.

**Что входит в Middle-уровень:**

- **Настройка workflow с нуля:** вы пишете YAML-файлы GitHub Actions (или GitLab CI) для документации: build → lint → test → deploy. Вы понимаете триггеры (`on: push`, `on: pull_request`), jobs и steps.
- **Выбор инструментов проверки:** вы настраиваете линтеры (Vale для стиля, markdownlint для форматирования), проверку ссылок (lychee, linkchecker), проверку орфографии (cspell, yaspeller). Вы понимаете, какие проверки обязательны, а какие — рекомендательны.
- **Проверка сборки:** вы настраиваете CI так, чтобы сборка сайта запускалась при каждом PR. Если сборка падает — PR не может быть смержен. Это гарантирует, что в main всегда попадает рабочая документация.
- **Автоматический деплой:** вы настраиваете пайплайн, который после merge в main собирает и публикует документацию автоматически. Вы понимаете разницу между staging и production деплоем.
- **Оптимизация пайплайна:** вы используете кэширование зависимостей, matrix builds (для нескольких версий), условные проверки (только для изменённых файлов). Это ускоряет CI и экономит ресурсы.
- **Мониторинг:** вы настраиваете уведомления о падениях CI (Slack, email), отслеживаете статус сборок, анализируете причины частых падений.

*Ключевой принцип Middle: вы **настраиваете и автоматизируете**. Вы отвечаете за то, чтобы CI/CD-пайплайн был надёжным, быстрым и покрывал все критические проверки.*

---

### Курсы и книги (Middle)

[GitHub Actions: The Complete Guide from Beginner to Expert (Udemy)](https://www.udemy.com/course/github-actions-the-complete-guide/) - Комплексный курс по GitHub Actions: от базовых workflow до продвинутых сценариев. Подходит для настройки CI/CD для документации;

[GitLab CI/CD: The Complete Guide (Udemy)](https://www.udemy.com/course/gitlab-ci-cd-the-complete-guide/) - Альтернатива GitHub Actions: настройка пайплайнов в GitLab CI. Полезно, если компания использует GitLab;

[Docs-as-Code Setup Guide (GitHub)](https://github.com/ann-kilzer/docs-as-code-setup-guide) - Comprehensive guide: CI/CD pipelines для документации, автоматизация проверок, best practices;

[Vale Documentation](https://vale.sh/docs/) - Официальная документация Vale: настройка правил, интеграция с CI;

[Continuous deployment for documentation (Ubuntu)](https://ubuntu.com/blog/continuous-deployment-for-documentation) - Реальный кейс: как организован CI/CD для документации в Ubuntu: review, test suite, deploy.
