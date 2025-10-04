# ALX System Engineering & DevOps - Shell Variables and Expansions 

This repository contains a series of bash scripts focused on mastering shell variables, expansions, and text manipulation for the ALX Software Engineering program. Each script solves a specific problem, demonstrating concepts from basic variable assignment to complex, multi-step text processing and base conversion puzzles. 

--- 

## 📜 Scripts Overview

| Filename                  | Description                              | Key Concept(s)                  |
|---------------------------|------------------------------------------|---------------------------------|
| `0-alias`                 | Creates a temporary alias (educational). | `alias`                         |
| `1-hello_you`             | Greets the current Linux user.           | `$USER`                         |
| `2-path`                  | Adds a directory to the PATH.            | `export`, `$PATH`               |
| `3-paths`                 | Counts directories in the PATH.          | Piping, `tr`, `grep`            |
| `4-global_variables`      | Lists all environment variables.         | `printenv`, `sort`              |
| `5-local_variables`       | Lists all shell variables and functions. | `set`                           |
| `6-create_local_variable` | Creates a local variable.                | Variable assignment             |
| `7-create_global_variable`| Creates a global variable.               | `export`                        |
| `8-true_knowledge`        | Performs shell addition.                 | `$((...))`                      |
| `9-divide_and_rule`       | Performs shell division.                 | `$((...))`                      |
| `10-love_exponent_breath` | Performs exponentiation.                 | `**`                            |
| `11-binary_to_decimal`    | Converts binary to decimal.              | Base conversion                 |
| `12-combinations`         | Prints filtered two-letter combinations. | Brace expansion, `grep`         |
| `13-print_float`          | Formats number to two decimal places.    | `printf`                        |
| `100-decimal_to_hexadecimal` | Converts decimal to hex.              | `printf`                        |
| `101-rot13`               | Encodes text with ROT13 cipher.          | `tr`                            |
| `102-odd`                 | Prints every other line from input.      | `paste`, `cut`                  |
| `103-water_and_stir`      | Arithmetic in custom bases.              | Advanced `tr` & base conversion |


---

## 💡 Key Concepts 

Mastered This project provided hands-on experience with core shell scripting concepts, including: 
- **Variable management**: local vs global 
- **Shell expansions**: arithmetic and brace expansions 
- **Text processing**: through piped commands (`tr`, `grep`, `cut`, `printf`) 
- **File permissions**: importance of `chmod +x` 
- **Cross-platform compatibility**: handling LF vs CRLF line endings 

--- 
## 🛠️ Tools Used 
- VS Code
- Bash  
- Coreutils (`tr`, `grep`, `cut`, `printf`) 
- Git & GitHub