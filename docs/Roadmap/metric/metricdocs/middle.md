## Middle: «Настраиваю сбор метрик и анализирую данные для улучшения документации»

На Middle-уровне метрики перестают быть просто «наблюдением». Теперь это **инструмент управления качеством**: вы настраиваете сбор данных, анализируете их и используете для принятия решений. Ключевой сдвиг: вы перестаёте быть пассивным получателем отчётов и становитесь тем, кто **определяет, что и как измерять**.

**Что входит в Middle-уровень:**

- **Настройка аналитики:** Вы настраиваете Google Analytics 4 (или Plausible) для документационного сайта: custom dimensions (doc_version, doc_section, search_query), custom events (code_copy, feedback_submitted).
- **Настройка поисковой аналитики:** Вы работаете с Algolia Analytics или встроенной поисковой аналитикой, чтобы отслеживать search success rate, zero-result rate и популярные запросы.
- **Анализ данных для принятия решений:** Вы не просто смотрите на цифры, а задаёте вопросы: почему у этой страницы высокий bounce rate? Почему пользователи ищут «X», но не находят? Какие темы генерируют больше всего тикетов в поддержку?
- **Построение дашбордов:** Вы создаёте дашборд (в Google Looker Studio, Power BI или аналоге), который показывает ключевые метрики в динамике: search success rate, ticket deflection, time-to-first-success.
- **Связывание метрик с бизнес-целями:** Вы понимаете, как метрики документации связаны с бизнес-показателями: adoption продукта, retention, cost-to-serve. Вы можете оценить экономию, например, зная среднюю стоимость одного обращения в поддержку (около $15–$25) и достигнутый уровень ticket deflection[reference:1].
- **A/B-тестирование:** Вы можете провести простой эксперимент: изменить структуру статьи или заголовок и сравнить метрики до и после.
- **Работа с поддержкой:** Вы налаживаете процесс обмена данными с поддержкой: какие тикеты можно было предотвратить с помощью документации?

*Ключевой принцип Middle: Вы **настраиваете и анализируете**. Вы отвечаете за то, чтобы данные были точными, а выводы — действенными.*

---

### Курсы и книги (Middle)

[How to Reduce Support Tickets With Better Documentation (Technical Writing Success Podcast)](https://podscan.fm/podcasts/technical-writing-success/episodes/how-to-reduce-support-tickets-with-better-documentation-with-real-numbers) - Эпизод о том, как рассчитать ROI документации через снижение затрат на поддержку, и о достижении ticket deflection rate в 25–60%;

[Explore KPIs and benchmarks for measuring content ROI (Zoomin Software)](https://www.zoominsoftware.com/blog/kpis-benchmarks-measuring-content-roi/) - Статья о ключевых показателях эффективности и бенчмарках для измерения ROI технического контента;

[Applied Theory: Adding Value as a Professional Technical Communicator (Janice Redish)](https://redish.net/wp-content/uploads/Redish_Applied_Theory_2010.pdf) - Классическая работа, объясняющая концепцию добавленной стоимости и то, как рассчитать возврат инвестиций (ROI) в техническую коммуникацию;

[Docs for Developers (Jared Bhatti et al.)](https://link.springer.com/book/10.1007/978-1-4842-7295-1) - Практическое руководство по измерению эффективности документации и построению процессов вокруг данных;

[Google Analytics 4 Documentation](https://support.google.com/analytics/answer/10089681) - Официальная документация GA4 для настройки кастомных событий и параметров.
