
---
# Битовая схема
![[Схема HOW слова.png]]

| Биты | Формат              | Часть                                                              |
| ---- | ------------------- | ------------------------------------------------------------------ |
| $17$ | `xxxxxxxxxxxxxxxxx` | **[[Truncated Time of the Week Message (TOW Message Truncated)]]** |
| $1$  | `x`                 | **[[Alert Flag]]**                                                 |
| $1$  | `x`                 | **[[Anti-Spoof Flag (A-S Flag)]]**                                 |
| $1$  | `x`                 | **[[Anti-Spoof Flag (A-S Flag)]]**<br>                             |
| $3$  | `xxx`               | **[[Subframe ID]]**<br>                                            |
| $2$  | `xx`                | **[[Handover World Parity Preserve Bits]]**<br>                    |
| $6$  | `xxxx00`            | **[[Parity Bits (P)]]**                                            |
