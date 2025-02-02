# Ruby Instance Variable Immutability without Accessor Methods

This repository demonstrates a subtle issue in Ruby related to instance variable access. When you define a method to access an instance variable (like the `value` method in the example), but don't use `attr_accessor`, `attr_reader`, or `attr_writer`, the instance variable becomes effectively immutable from outside the class.

The `bug.rb` file shows this behavior.  The `bugSolution.rb` file shows how to use `attr_accessor` to fix it.