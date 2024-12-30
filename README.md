# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue when directly modifying an object's instance variable using `instance_variable_set` in Ruby.  While it works, it bypasses any potential safeguards or internal logic within the class, potentially causing unexpected behavior or breaking encapsulation.

The `bug.rb` file shows the problem. The `bugSolution.rb` file offers a solution using accessor methods.