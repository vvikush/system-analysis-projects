# Diagrams

Папка содержит диаграммы и визуальные модели по системе управления доставкой заказов.

## Состав диаграмм

| Файл | Диаграмма | Назначение |
|---|---|---|
| [onion-diagram.png](./onion-diagram.png) | Onion Diagram | Показывает стейкхолдеров системы и их близость к решению. |
| [context-diagram.png](./context-diagram.png) | Context Diagram | Показывает границы системы DEL и обмен данными с внешними участниками. |
| [er-diagram.png](./er-diagram.png) | ER Diagram | Показывает основные сущности модели данных и связи между ними. |
| [data-flow-diagram.png](./data-flow-diagram.png) | Data Flow Diagram | Показывает потоки данных между системой и участниками процесса доставки. |
| [swimlane-diagram.png](./swimlane-diagram.png) | Swimlane Diagram | Показывает распределение ответственности между ролями в процессе доставки. |
| [additional-swimlane-diagram.png](./additional-swimlane-diagram.png) | Additional Swimlane Diagram | Показывает процесс доставки с создаваемыми и обновляемыми артефактами. |
| [state-diagram.png](./state-diagram.png) | State Diagram | Показывает жизненный цикл заказа на доставку. |

## Назначение

Диаграммы дополняют текстовые аналитические материалы и помогают быстро понять:

- кто участвует в процессе доставки;
- какие внешние участники взаимодействуют с системой;
- какие данные передаются между участниками;
- какие сущности лежат в основе модели данных;
- как распределена ответственность между ролями;
- какие артефакты создаются и обновляются в процессе;
- как меняется состояние заказа на доставку.

## Связь с основными файлами

| Диаграмма | Где используется |
|---|---|
| Onion Diagram | [stakeholders.md](../stakeholders.md) |
| Context Diagram | [process-modeling.md](../process-modeling.md) |
| ER Diagram | [data-model.md](../data-model.md) |
| Data Flow Diagram | [process-modeling.md](../process-modeling.md) |
| Swimlane Diagram | [process-modeling.md](../process-modeling.md) |
| Additional Swimlane Diagram | [process-modeling.md](../process-modeling.md) |
| State Diagram | [process-modeling.md](../process-modeling.md) |

## Итог

Набор диаграмм показывает разные стороны системы доставки: участников, границы системы, данные, процессы, распределение ответственности и жизненный цикл заказа.
