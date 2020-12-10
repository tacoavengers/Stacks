# Stacks
Stacks    
https://repl.it/@webdevdave/Stacks#main.py

### How it works

Stack is a data structure that works on the LIFO model: Last In First Out.    
It works on ```push``` (e.g., append) and ```pop```(e.g., remove the top most element).            
It also usese ```.isEmpty()```, a boolean to return a T/F if the stack is empty or not.    
And ```peak``` that finds an item at the top of the stack.    

#### Time complexity

* Push an item to the stack is 0(1)
* Pop an item from the stack is 0(1)
* Peak an item (find the item at top) is 0(1)
* Space complexity is 0(n) because it takes time to store the data

#### Pros
* Push, Pop and Peak are 0(1)

#### Con
* Stacks are not very versatile

#### Usefulness
* Running programs
* Call stack
* Tracking nodes
* Parsing strings

#### Examples

* 1
```
stack = []

stack.append(10)
stack.append(20)
stack.append(30)

print(stack) // [10, 20, 30]

stack.pop()
print(stack) // [10, 20]
```

* 2
```
stack = []
def push():
  element = input("Enter an element: ")
  stack.append(element)
  print(stack)
  

```

### Stacks vs Queues

* Queue: FIFO/LILO   -> A line of people
* Stack: LIFO/FILO   -> A stack of plates


