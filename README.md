# Unexpected Behavior with Direct Instance Variable Manipulation in Ruby

This example demonstrates the potential pitfalls of directly manipulating instance variables in Ruby using `instance_variable_set` and `instance_variable_get`.  While technically possible, it often leads to code that's harder to understand, maintain, and debug.  It bypasses established access methods and breaks encapsulation. 

**Best practice:** Access instance variables via well-defined getter and setter methods whenever possible to improve code clarity and maintainability.