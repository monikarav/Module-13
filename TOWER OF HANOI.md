# Exp.No: 5  
## SEB

### AIM  

To Write a Python program to implement stack using List and its built-in methods ( append(), pop()). 

### ALGORITHM  

1. Start the program.
   
2. Initialize Stack: Create an empty list stack to represent the stack.

3. Define Class st: Define a class with methods push, pop, and peek to perform stack operations.

4. Push Method: The push(self, S) method adds all elements of list S to the global stack using a loop.

5. Pop Method: The pop(self) method removes the top element from the stack and prints it if the stack is not empty; otherwise, it prints "stack is empty".

6. Peek Method: The peek(self) method prints all elements currently in the stack if it is not empty.

7. Create Input List: Read an integer input size, and generate a list l containing all odd numbers from 1 to size-1.

8. Perform Operations: Push list l onto the stack, display stack contents using peek(), pop the top element, and display the stack again.

9. stop the program.

### PROGRAM  

```
stack = []
class st:
    def push(self,S):
        for i in S:
            stack.append(i)
        return
    def pop(self):
        if stack:
            print("Element popped : ",stack.pop())
        else:
            print("stack is empty")
        return
    def peek(self):
        if stack:
            print("Elements in the stack\n",stack)
        return
    
s=st()
size=int(input())
l=[i for i in range(1,size) if i%2!=0]
s.push(l)
s.peek()
s.pop()
s.peek()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/da91ac45-e3ee-4b37-b208-5ef5d182a109)

### RESULT

Thus the implementation of Python program for stack using List and its built-in methods ( append(), pop()) was successfully verified. 

