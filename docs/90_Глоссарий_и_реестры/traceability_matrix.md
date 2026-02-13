# Матрица трассировки требований

## Metadata
- ID документа: DOC-REG-TRACE-0001
- Статус: draft
- Версия: 0.1
- Дата создания: 2026-02-13
- Дата последнего изменения: 2026-02-13

| REQ ID | Источник | L2 | L3 OP | L4 UX/Code | Тест/проверка | Статус |
|---|---|---|---|---|---|---|
| REQ-L1-ECON-0001 | L1 §2.1 | L2_economy_money-flow_and_liquidity | OP-ECON-0001 | L4_CODE_economy_invariants_and_formulas | Проверка замкнутости потока | draft |
| REQ-L1-MARKET-0002 | L1 §2.2 | L2_player_markets_trade_and_rent | OP-ECON-0002 | L4_UX_market_and_contract_flows + L4_CODE_economy_invariants_and_formulas | Атомарность сделки | draft |
| REQ-L1-LIFE-0002 | L1 §2.4 | L2_lifecycle_aging_and_entropy | OP-SIM-0001 | L4_CODE_economy_invariants_and_formulas | Тик старения | draft |
| REQ-L1-LABOR-0004 | L1 §2.5 | L2_labor_productivity_and_wellbeing | OP-SOC-0001 | L4_CODE_state_aggregation_model | Diminishing returns | draft |
| REQ-L1-ANTI-MONO-0001 | L1 §2.6 | L2_conflict_risk_and_labor_stability | OP-SOC-0002 | L4_CODE_economy_invariants_and_formulas | Антимонополизационные стресс-тесты | draft |
| REQ-L1-SCALE-0003 | L1 §2.7 | L2_scale_transition_single_to_settlement | OP-SOC-0003 | L4_UX_hex_state_indicator_and_progressive_revelation + L4_CODE_state_aggregation_model | Progressive revelation | draft |

## История изменений
- v0.1 — создана начальная матрица трассировки по приоритетным REQ.
