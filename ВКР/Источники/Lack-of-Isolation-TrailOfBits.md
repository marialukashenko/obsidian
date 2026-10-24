---
title: "Lack of isolation in agentic browsers resurfaces old vulnerabilities"
authors: Trail of Bits (Lucas Bourtoule и др.)
date: 2026-01-13
tags: [source, motivation, trust-zones]
link: https://blog.trailofbits.com/2026/01/13/lack-of-isolation-in-agentic-browsers-resurfaces-old-vulnerabilities/
---

# Lack of isolation in agentic browsers (Trail of Bits)

**Что сделано.** Практический (не академический) анализ того, что агентные браузеры по сути возвращают давно решённые в вебе проблемы изоляции (аналогия с XSS) — потому что агент как единая "привилегированная" сущность стирает границы trust zones между origin'ами, с которыми он работает.

**Почему важно для ВКР.** Хороший источник для введения/мотивации в основном тексте — независимое от академии (индустриальное, security-focused) подтверждение центрального тезиса: нужны детерминированные системные границы, а не надежда на модель. Также полезная терминология "trust zones" для описания архитектуры в Разделе 2 модели угроз.

**Прочитать:** разбор конкретных аналогий с классическими веб-уязвимостями — удобно для explaining "почему это не новая проблема, а старая в новой обёртке" в защите диплома.
