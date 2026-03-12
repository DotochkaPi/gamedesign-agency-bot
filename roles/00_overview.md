# Game Design Agency — Структура и роли

## Полная цепочка взаимодействия

`
Пользователь
    ↓
Creative Director          ← принимает задачу, формирует видение
    ↓ раздаёт задачи
┌─────────────────────────────────────┐
│  Concept Designer                   │
│  Systems Designer                   │ → специалисты делают свои части
│  Narrative Designer                 │
│  Level Designer                     │
│  Monetization Designer              │
│  Market Analyst                     │
└─────────────────────────────────────┘
    ↓ все материалы
Lead Game Designer         ← собирает единый GDD
    ↓ финальный GDD
GDD Reviewer               ← ревью: находит ошибки, адресует специалистам
    ↓ замечания по ролям
Специалисты                ← правят свои части (одна итерация)
    ↓ исправления
GDD Reviewer               ← проверяет закрытие замечаний
    ↓ финальный документ
Creative Director          ← утверждает, выдаёт результат пользователю
    ↓
Пользователь
`

## Роли

| # | Роль | Файл | Место в цепочке |
|---|------|------|-----------------|
| — | Creative Director | 01_creative_director.md | Начало и конец цепочки |
| — | Project Manager | 02_project_manager.md | Контроль процесса на всех этапах |
| 1 | Concept Designer | 03_concept_designer.md | Draft-концепции |
| 2 | Systems Designer | 04_systems_designer.md | Механики и баланс |
| 3 | Narrative Designer | 05_narrative_designer.md | Сюжет и мир |
| 4 | Level Designer | 06_level_designer.md | Уровни и прогрессия |
| 5 | GDD Writer | 07_gdd_writer.md | Оформление документа |
| 6 | Monetization Designer | 08_monetization_designer.md | Монетизация и экономика |
| 7 | Market Analyst | 09_market_analyst.md | Анализ рынка |
| 8 | Playtesting Lead | 10_playtesting_lead.md | Сценарии тестирования |
| — | Lead Game Designer | 00b_lead_game_designer.md | Сборка финального GDD |
| — | GDD Reviewer | 00c_gdd_reviewer.md | Ревью и итерация правок |

## Правила работы

- **Одна итерация ревью** — GDD Reviewer делает ревью один раз, замечания закрываются, документ идёт дальше
- **Адресные замечания** — каждая правка направляется конкретному специалисту
- **Creative Director** — финальная инстанция, утверждает результат
- **Project Manager** — следит за процессом на всех этапах, не генерирует контент