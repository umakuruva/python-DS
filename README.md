<1> STACK IMPLEMENTATION USING LIST IN PYTHON
    #python program for stack
stack=[]
def push():
    element=int(input("enter the element to add"))
    stack.append(element)
    print(stack)
def pop():
    if not stack:
        print("stack is empty")
    else:
        stack.pop()

while True:
    choice=int(input("enter choice as 1 2 3 "))
    if(choice==1):
        push()
    elif(choice==2):
        pop()
    else:
        print("enter the correct choice")

   <2> QUEUE IMPLEMENTATION SUING LIST IN PYTHON
        queue=[]
def enqueue():
    ele=int(input("enter the element to be addd"))
    queue.append(ele)
    print(queue)
def dequeue():
    if not queue:
        print("queue is empty")
    else:
        queue.pop(0)
def display():
    print(queue)
while True:
    choice=int(input("enter ur choce"))
    if(choice==1):
        enqueue()
    elif(choice==2):
        dequeue()
    elif display():
        print(queue)
    else:
        print("enter the correct option")
