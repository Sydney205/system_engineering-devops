# 0x03-shell_variables_expansions

Scripts to practice shell variables, environment variables, aliases, and arithmetic operations in Bash.

## Scripts

### 0. <o> (0-alias)
Create an alias `ls` with the value `rm *`.  
Example: after sourcing the script, executing `ls` will remove all files in the current directory.

### 1. Hello you (1-hello_you)
Print `hello user`, where `user` is the current Linux user.  

### 2. The path to success is to take massive, determined action (2-path)
Add `/action` to the `PATH` environment variable, ensuring it is the last directory in the search path.  

### 3. If the path be beautiful, let us not ask where it leads (3-paths)
Count the number of directories listed in the `PATH` and print the total.  

### 4. Global variables (4-global_variables)
List all environment variables currently set in the shell session.  

### 5. Local variables (5-local_variables)
List all local variables, environment variables, and shell functions.  

### 6. Local variable (6-create_local_variable)
Create a new local variable:  
- Name: `BEST`  
- Value: `School`  

### 7. Global variable (7-create_global_variable)
Create a new global variable:  
- Name: `BEST`  
- Value: `School`  

### 8. Every addition to true knowledge is an addition to human power (8-true_knowledge)
Print the result of adding `128` to the value stored in the environment variable `TRUEKNOWLEDGE`.  

### 9. Divide and rule (9-divide_and_rule)
Print the result of dividing the environment variable `POWER` by `DIVIDE`.  

### 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath (10-love_exponent_breath)
Print the result of `BREATH` raised to the power of `LOVE`.  

## Usage
Make scripts executable with `chmod +x <script>` and run with `./<script>`.