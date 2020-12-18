# BadProgrammingAdvice

- Always convert every numerical value to as small a value as possible, if possible, to something less than 0.1. Smaller values take up less memory.
- Worried about being asked to change a feature in the future? Make sure you declare it as a ```const``` so it can never be changed. Everybody knows that ```const``` means it's permanent code that can't be altered.
