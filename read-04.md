## What’s the difference between a static and an instance constructor?

 Static constructors are used to set up things that are common to all instances of a class, and they run only once. Instance constructors are used to set up things that are specific to each individual object created from the class, and they run whenever a new object is created.

## How does the use of a static constructor differ from setting properties/values?

A static constructor is used to perform one-time initialization tasks for all instances of a class before any object is created or any static member is accessed. It allows you to set up shared resources or initialize static variables. On the other hand, setting properties/values is a way to configure individual object instances with specific values after they are created, allowing customization and variation between different objects.


## Knowing what you now know about the stack and the heap, how might you rethink the way you did projects in previous courses, to make more effecient use of memory?

Understanding the stack and the heap can help optimize memory usage in previous projects. By minimizing the use of large data structures on the stack, such as arrays or objects, and allocating them on the heap instead, we can avoid stack overflows and efficiently manage memory. Additionally, utilizing stack allocation for smaller, short-lived variables and objects can improve memory efficiency by automatically deallocating them when they go out of scope.

## Compare “Garbage Collection” in C# with the lifecycle of normal household items.

Garbage collection in C# is like having a cleaning service for your house. It automatically identifies and collects unused objects in your program's memory, freeing up space for new objects. Just as you don't need to worry about throwing away old, unwanted items in your house, garbage collection handles the memory management for you in C# without manual intervention.
