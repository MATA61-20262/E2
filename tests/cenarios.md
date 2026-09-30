# Cenários


| **Cenário** | **Entrada**               | **Saída esperada** |
| Expressão Padrão  | 90 * 100 / 18.0 - 48 + 77 | expressão sem erro sintático. |
| Expressão simples | 3.1415 | expressão sem erro sintático. |
| Associatividade + | 2 + 3 + 4.0 | expressão sem erro sintático. |
| Associatividade * | 2 * 3 * 4.0 | expressão sem erro sintático. |
| Precedência * sobre + | 2 + 3 * 4.0  expressão sem erro sintático. |
| Espaçamento denso | 90*100/18.0-48+77 | expressão sem erro sintático. |
| Erro Léxico (1) | 45 $ 2 | expressão com erro sintático. |
| Erro Léxico (2) | (45 - 2) | expressão com erro sintático. |
| Operador sem operando (1) | 90 * 100 / 18.0 - + 77 | expressão com erro sintático. |
| Operador sem operando (2) | * 90 100 / 18.0 - 48 + 77 | expressão com erro sintático. |
| Operador sem operando (3) | 90 * 100 / 18.0 - 48 + | expressão com erro sintático. |
| Operandos sem operador | 90 * 100 18.0 - 77 | expressão com erro sintático. |

