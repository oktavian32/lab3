Memory Tests Lab
Topic: Memory (Stack/Heap), Garbage Collection, Passing Arguments by Value/Reference, Unit Tests
Programming Language: C#
Concepts
Value Types: Stored on the stack, passed by value.
Reference Types: Stored on the heap, passed by reference.
Garbage Collector: Automatically manages memory deallocation for unused objects.

Test Descriptions

ValueTypeIsPassedByValue:
Demonstrates that value types are passed by value, i.e., copied.

ReferenceTypeIsPassedByReference:
Demonstrates that reference types are passed by reference, i.e., the object's address is passed.

ObjectIsCreatedOnHeap:
Creates an object on the heap. The test does not directly verify the location but ensures the call does not throw exceptions.

ObjectIsCreatedOnStack:
Creates an object on the stack. The test does not directly verify the location but ensures the call does not throw exceptions.

GarbageCollectorWorks:
Invokes the garbage collector to demonstrate its functionality. The test verifies that calling GC.Collect() does not throw exceptions.
