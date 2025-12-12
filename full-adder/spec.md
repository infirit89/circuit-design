# Full adder

### Truth table
| A | B | Carry(in) | Result | Carry(out) |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

Result = \~A * ~B * C + \~A * B * \~C + A * \~B * \~C + A * B * C

Carry(out) = ~A * B * C + A * ~B * C + A * B * \~C + A * B * C
