# Stacks and Queues:
In C#, a stack is a data structure that follows the Last-In-First-Out (LIFO) principle. It is a collection of elements where the last element added is the first one to be removed. You can think of it as a stack of objects, where you can only interact with the topmost element.

In C#, the `Stack<T>` class is provided as part of the .NET Framework to implement a stack. The `T` represents the type of elements that the stack will hold.

Here's an example of how you can work with a stack in C#:

```csharp
Stack<int> stack = new Stack<int>();

// Pushing elements onto the stack
stack.Push(1);
stack.Push(2);
stack.Push(3);

// Getting the topmost element
int topElement = stack.Peek(); // Returns 3

// Removing and retrieving the topmost element
int removedElement = stack.Pop(); // Returns 3

// Checking if the stack is empty
bool isEmpty = stack.Count == 0;

// Iterating over the elements in the stack
foreach (int element in stack)
{
    Console.WriteLine(element);
}
```

In the above example, we create a stack `stack` that holds integers. We push three elements onto the stack using the `Push` method. 
Then, we use the `Peek` method to get the topmost element without removing it, and the `Pop` method to remove and retrieve the topmost element. 
We can check if the stack is empty by inspecting the `Count` property. Finally, we can iterate over the elements in the stack using a foreach loop

Here are some examples that demonstrate how to use the push, pop, and other methods of the `Stack<T>` class in C#:

```csharp
Stack<string> stack = new Stack<string>();

// Pushing elements onto the stack
stack.Push("Apple");
stack.Push("Banana");
stack.Push("Orange");

// Getting the topmost element
string topElement = stack.Peek(); // Returns "Orange"

// Removing and retrieving the topmost element
string removedElement = stack.Pop(); // Returns "Orange"

// Checking if the stack is empty
bool isEmpty = stack.Count == 0;

// Iterating over the elements in the stack
foreach (string element in stack)
{
    Console.WriteLine(element);
}
```

In this example, we create a stack `stack` that holds strings. We push three string elements onto the stack using the `Push` method. Then, we use the `Peek` method to get the topmost element ("Orange") without removing it, and the `Pop` method to remove and retrieve the topmost element. We can check if the stack is empty by inspecting the `Count` property. Finally, we can iterate over the elements in the stack using a foreach loop and print each element.

Here's the output you would see when running this code:

```
Banana
Apple
```

As we remove elements from the stack using `Pop`, the topmost element ("Orange") is removed first, followed by "Banana", leaving "Apple" as the only element in the stack.
