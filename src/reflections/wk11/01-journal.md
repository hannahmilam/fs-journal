# C#

## What does Inheritance accomplish for us in C#?
Extending properties to your class from the parent class. This helps remove repeated code. 

## How does Member inheritance work in C#? Does a class inherit all members of the base class?
 Everything is inherited except for constructors and child finalizers, but whether it'll be visible or not depends on the member's visibility.

## How does accessibility affect inheritance?
If a class is public then everything can access it, if it's private only that class can access it, and if it's internal then anything in that application can access it.
