
---
# Битовая схема
![[Схема TLM слова.png]]

| Биты | Формат           | Часть                                    |
| ---- | ---------------- | ---------------------------------------- |
| $8$  | `10001011`       | **Preamble**                             |
| $14$ | `xxxxxxxxxxxxxx` | **[[Telemetry Message (TLM Message)]]**  |
| $2$  | `11`             | **[[Telemetry Word Reserved Bits (C)]]** |
| $6$  | `xxxxxx`         | **[[Parity Bits (P)]]**                  |

