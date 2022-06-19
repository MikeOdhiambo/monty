## MONTY

### The Monty Language
**Monty 0.98 is a scripting language** that is first compiled into **Monty** byte codes (Just like Python). <br> It relies on a unique stack, with specific instructions to manipulate it. **The goal of this project is to <br> create an interpreter for Monty ByteCodes files**.

---
### The monty program
**Usage**: ```monty file``` <br>
- where ```file``` is the path to the file containing Monty byte code

---
### Installation
```
git clone https://github.com/MikeOdhiambo/monty
```
### Compilation
```
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```
