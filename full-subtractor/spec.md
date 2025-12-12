# Full subtractor

### Truth table
| A | B | Borrow(in) | Result | Borrow(out) |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 1 |
| 0 | 1 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 0 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 0 | 0 |
| 1 | 1 | 1 | 1 | 1 |

Result = \~A * \~B * C + \~A * B * \~C + A * \~B * \~C + A * B * C

Borrow(out) = \~A * \~B * C + \~A * B * \~C + A * B * C
