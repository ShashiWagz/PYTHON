# PYTHON
## Assignment 01
#### 2022/09/28
### **Loku Geeganage Sandushi Wagmini**

# Program make a simple calculator

def simple_Calculator(num1,num2,choise):
    
    if choise == 'a':
        return num1 + num2     # Add two integers
    elif choise == 's':
        return num1 - num2     # subtract two integers
    elif choise == 'm':
        return num1 * num2     # Multiply two integers
    elif choise == 'd':
        return num1 / num2     # Divide two integers
    else:
        print("Invalid choise")
        
print("Output :",simple_Calculator(2,5,'d'))

code
