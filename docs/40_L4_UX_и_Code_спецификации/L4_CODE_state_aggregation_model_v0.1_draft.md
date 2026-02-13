# L4 Code: Модель агрегации состояний

## Metadata
- ID документа: DOC-L4-CODE-AGGR-0001
- Уровень: L4
- Статус: draft
- Версия: 0.1

## Цель
Определить техническую схему агрегации индикаторов от сущности к группе/поселению.

## Зависимости
- Родительские: L3_OP-SOC-0003, L2_scale_transition_single_to_settlement_v0.1_draft.md

## Содержание уровня
- Входные наборы: entity_state[], selection_scope.
- Агрегаторы: mean, weighted mean, risk envelope, worst-case cap.
- Visibility policy: hidden_until_discovered flag.
- Выход: unified_state_payload для UI и аналитики.

## Критерии готовности
- Описаны API-контракты входа/выхода и стратегия кэширования.

## История изменений
- v0.1 — первый черновик.
