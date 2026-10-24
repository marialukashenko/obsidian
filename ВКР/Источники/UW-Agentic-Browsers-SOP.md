---
title: "Agentic Browsers and the Same-Origin Policy"
authors: Roesner, Kohlbrenner (University of Washington, Security & Privacy Lab)
date: 2026-06-15
tags: [source, origin-control, motivation]
link: https://arxiv.org/pdf/2606.14027
project_page: https://agent-security.cs.washington.edu/agentic_browsers_sop.html
uw_news: https://www.washington.edu/news/2026/06/30/some-agentic-ai-browsers-come-with-major-cybersecurity-risks-uw-study-finds/
---

# Agentic Browsers and the Same-Origin Policy

**Что сделано.** Проверили 7 агентных браузеров (в т.ч. ChatGPT Atlas в Agent Mode, Perplexity Comet, и др.) на соблюдение same-origin policy. Показали PoC полноценной кражи кросс-origin данных на Atlas; часть агентов читает кросс-доменные iframe без ограничений.

**Почему важно для ВКР.** Это мотивирующая картина всей проблемы: агент как "суперпользователь" браузера ломает SOP, потому что контроль происхождения данных не встроен в сам механизм работы с контекстом. Ссылаться на эту статью в Разделе 3/6 модели угроз как источник эмпирических данных об актуальности origin-угрозы.

**Статус в роадмапе.** Baseline-мотивация. Защита для этого класса угроз закрыта SOPGuard (см. [[SOPGuard]]), не переделываем.

**Прочитать:** введение + раздел с PoC на Atlas (там же есть таблица по всем 7 браузерам — пригодится для Раздела 5/6 модели угроз, если нужно сослаться на конкретные капабилити нарушителя).
