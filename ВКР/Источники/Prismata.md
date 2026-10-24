---
title: "Prismata: Confining Cross-Site Prompt Injection in Web Agents"
tags: [source, argument-control, defense]
link: https://arxiv.org/pdf/2607.08147
arxiv: 2607.08147
---

# Prismata

**Что сделано.** Защитный механизм на основе contextual least privilege — определяет "критические пути" в DOM/задаче агента и ограничивает, какие данные и действия доступны агенту в каждый момент, снижая поверхность для cross-site prompt injection.

**Почему важно для ВКР.** Вторичный источник для argument/origin-control baseline — дополняет PACT и SOPGuard альтернативным подходом (least privilege по DOM, а не только по данным/аргументам). Полезен как материал для обзора существующих решений в основном тексте (чтобы показать, что baseline — не единственное решение, а представитель целого класса), и как возможная альтернатива/дополнение, если SOPGuard+PACT окажется неудобно интегрировать в стенд.

**Статус:** не baseline по умолчанию, но запасной вариант.
