The TwoStack class is the main class that controls the execution of the program. It interacts with the user to perform operations on two stacks.

Here's what the TwoStack class does:

1. It takes input from the user, including the number of test cases (T) and the queries for each test case (Q).
2. For each test case, it creates an instance of the twoStacks class to simulate two stacks.
3. It then processes the queries for each test case.
4. The queries can be of two types:
    # Type 1: Push an element onto one of the two stacks.
    # Type 2: Pop (remove) an element from one of the two stacks and print it.
5. Based on the user's input, the code calls the appropriate methods of the twoStacks class to push or pop elements from the desired stack.
6. The popped elements are printed as output.

In simpler terms, the TwoStack class is like a manager that takes instructions from the user and performs actions on two separate stacks accordingly. It keeps track of the inputs, communicates with the twoStacks class, and displays the results.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Now, let's focus on the twoStacks class:

1. We have an array called arr that represents the stack.
2. There are two variables, top1 and top2, that keep track of the top positions of two stacks within the arr array.
3. We also have a constant n that represents the maximum size of the array.

The class provides four operations:

1. push1(int x): This operation adds an element x to the first stack. It does so by incrementing top1 and storing the element at that position in the arr array.
2. push2(int x): This operation adds an element x to the second stack. It does so by decrementing top2 and storing the element at that position in the arr array.
3. pop1(): This operation removes and returns the top element from the first stack. It does so by accessing the element at position top1 in the arr array and then decrementing top1.
4. pop2(): This operation removes and returns the top element from the second stack. It does so by accessing the element at position top2 in the arr array and then incrementing top2.

In the given code, these operations are called based on the user's input to simulate the behavior of two stacks. The user can choose to push elements onto either stack or pop elements from either stack. The code executes these operations according to the provided inputs and prints the popped elements.

Hope this explanation helps you understand the code better!
