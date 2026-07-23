# Наука обучения: механики и основания

Техники с сильнейшей доказательной базой (Dunlosky et al. 2013 и позднейшие мета-анализы). Автор урока встраивает их в шаблон, ревьюер проверяет наличие.

## Механики урока

1. **Pretest в начале:** 2–3 вопроса ДО контента. Даже ошибочные ответы с последующим разбором дают прирост усвоения против простого чтения (prequestion effect). Вопросы — на интуицию, не на знание терминов.
2. **Retrieval-блок в конце с обратной связью:** открытые вопросы («объясни», «рассчитай») сильнее узнавания; обратная связь после попытки обязательна (testing effect, g ≈ 0.5–0.6, Adesope 2017).
3. **Расписание повторений:** урок N включает retrieval-вопросы по уроку N−1 (интервал 1–2 дня) и N−3/N−4 (около недели). Оптимальный интервал — 10–20% от срока желаемого удержания (Cepeda 2008). Критерий усвоения понятия: успешно извлечено ≥3 раз в разных сессиях (successive relearning, Rawson & Dunlosky). Счётчик — в learning-log.jsonl.
4. **Refutation-блоки:** «типичный миф → почему он неверен → правильная модель». Одна из сильнейших техник для исправления заблуждений; разбирать только реально распространённые мифы — редкие мифы от повторения только закрепляются (familiarity backfire).
5. **Self-explanation / elaborative interrogation:** после ключевых идей — «объясни своими словами, почему X ведёт к Y»; наставник проверяет ответ в диалоге (Bisra 2018).
6. **Worked examples с fading** для процедурных навыков: полный разбор → пример без последнего шага → без двух → самостоятельно. Продвинутому пользователю (из Профиля) первые ступени пропускать — им они вредят (expertise reversal effect).
7. **Interleaving:** в практических блоках смешивать задачи из смежных тем, особенно где понятия легко спутать.
8. **Dual coding:** к каждой абстрактной концепции — содержательная mermaid-схема рядом с текстом. Декоративные схемы не считаются.
9. **Запрещено как основная нагрузка:** перечитывание, конспект-пересказ, выделение маркером — техники с низкой доказательностью. Их место занимают retrieval-задания. Желательная трудность полезна (Bjork & Bjork): лёгкость чтения ≠ усвоение.

## Принципы пайплайна

- **Диагностика до объяснений** (Mollick & Mollick): сначала выяснить, что человек знает и зачем ему тема, потом учить.
- **Backward design** (Wiggins & McTighe): от проверяемых результатов «смогу…» к контенту, не наоборот.
- **Mastery-based progression** (практика Khanmigo): дальше двигаются после проверки понимания. У нас — квиз-гейт, опция из Профиля с ручкой обхода.
- **Полнота против внешнего эталона:** LLM пишет программу из усреднённой памяти и систематически пропускает подтемы; лечится картой из оглавлений учебников + критиком пропусков с чистым контекстом (CRITIC: модель в собственном контексте пробелов не видит).

## Источники

- Dunlosky et al. 2013, рейтинг техник обучения: https://journals.sagepub.com/doi/abs/10.1177/1529100612453266
- Adesope et al. 2017, мета-анализ testing effect: https://journals.sagepub.com/doi/abs/10.3102/0034654316689306
- Rawson & Dunlosky 2022, successive relearning: https://journals.sagepub.com/doi/full/10.1177/09637214221100484
- Cepeda et al. 2008, оптимальные интервалы: https://laplab.ucsd.edu/articles/Cepeda%20et%20al%202008_psychsci.pdf
- Bisra et al. 2018, self-explanation: https://link.springer.com/article/10.1007/s10648-018-9434-x
- Bjork & Bjork 2020, desirable difficulties: https://www.waddesdonschool.com/wp-content/uploads/2021/02/Desriable-Difficulties-in-theory-and-practice-Bjork-Bjork-2020.pdf
- Refutation texts, мета-анализ 2025: https://www.tandfonline.com/doi/abs/10.1080/00461520.2024.2365628
- Wiggins & McTighe, backward design: https://fctl.ucf.edu/teaching-resources/course-design/backward-design/
- Mollick & Mollick, Assigning AI: https://arxiv.org/pdf/2306.10052
- Wharton Prompt Library: https://ai-analytics.wharton.upenn.edu/generative-ai-labs/instructor-prompt
- Google LearnLM, принципы педагогики: https://arxiv.org/html/2412.16429v1
- CRITIC: https://openreview.net/forum?id=Sx038qxjek
- Anthropic, multi-agent системы: https://claude.com/blog/building-multi-agent-systems-when-and-how-to-use-them
