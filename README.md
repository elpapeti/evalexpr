Same as the original [evalexpr](https://github.com/ISibboI/evalexpr), but with the next modified/added operators:

| Operator | Precedence | Description |
|----------|------------|-------------|
| / | 100 | Division (float in any case) |
| // | 100 | Integer division |
| % | 100 | Percentage |
| %% | 100 | Modulo (integer if both arguments are integers, otherwise float) |

Also deleted math:: from the math functions that needed it.
