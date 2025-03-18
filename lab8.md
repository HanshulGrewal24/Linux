Lab experiment-8

1. Write shell scripts to print system information.

Example-
lscpu

<img width="960" alt="image" src="https://github.com/user-attachments/assets/ab1b3cfc-4fa3-44a0-9c85-e95b98d339a9" />


2. Write shell script to perform basic mathematical calculation.

Example:
#!/bin/bash
echo "Enter the first number: "
read num1
echo "Enter the second number: "
read num2
echo "Addition: $((num1 + num2))"
echo "Subtraction: $((num1 - num2))"
echo "Multiplication: $((num1 * num2))"
echo "Division: $((num1 / num2))"

<img width="960" alt="image" src="https://github.com/user-attachments/assets/e991b9c4-7a2f-4ac9-8b06-6d0cd5b1f0ef" />

<img width="913" alt="image" src="https://github.com/user-attachments/assets/ce1df6dc-c4d0-4773-b95e-402f7af0687e" />


3. Use redirection operators to store the output of commands

#!/bin/bash
echo "Enter the cmds for direction"
read cmd
$cmd > file.txt
echo "File redirected successfully."

<img width="921" alt="image" src="https://github.com/user-attachments/assets/931d3035-f8fe-473f-8bb0-e21abbd02eb7" />

<img width="930" alt="image" src="https://github.com/user-attachments/assets/0ca0685f-f4b3-4a7e-a1d4-0f152bef4c85" />
