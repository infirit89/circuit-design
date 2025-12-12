# Multiplexer

### Truth table

| S1 | S0 | Result |
|---|---|---|
| 0 | 0 | D0 |
| 0 | 1 | D1 |
| 1 | 0 | D2 |
| 1 | 1 | D3 |

Result = \~S1 * \~S2 * D0 + \~S1 * S0 * D1 + S1 * \~S0 * D2 + S1 * S0 * D3
