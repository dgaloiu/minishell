# Minishell

The purpose of this project is to code in C a simple shell based on bash

## Features
### Builtins
Here's a short resume of the builtins implemented
| command | options | description |
|:---|:---|:---|
| **`cd`** | | change the working directory |
| **`echo`** | `-n` | print the argument string on the standard output |
| **`env`** | | print the environnement |
| **`exit`** | | cause normal process termination |
| **`export`** | | set export attribute for shell variables |
| **`pwd`** | |  print the full name of the actual work repertory |
| **`unset`** | | unset values and attributes of variables |

### Operators
* `'` singlequote
* `"` doublequote (expands variables)
* `|` pipe
* `<` standard input
* `>` standard output
* `<<` heredoc mode
* `>>` appending output

### Signals
* `Ctrl+C`
* `Ctrl+D`
* `Ctrl+\`

### Special
* `$VAR` for env variables expansion
* `$?` exit status of the last command

## Usage
```
git clone https://github.com/dgaloiu/minishell.git
cd minishell
make
```

