# OOP Homework: Understanding Object-Oriented Programming

### Question 1: Basic OOP Concept
**Q1.** Create a simple class `Person` that has the following attributes:
- `name`: a string for the person's name.
- `age`: an integer for the person's age.

Write a method `greet()` that prints `"Hello, my name is [name] and I am [age] years old."` where `[name]` and `[age]` are replaced with the actual values of the attributes.

---

### Question 2: Inheritance
**Q2.** Create a base class `Animal` with a method `sound()` that returns an empty string. Then, create two subclasses:
- `Dog` which overrides the `sound()` method to return `"Woof!"`.
- `Cat` which overrides the `sound()` method to return `"Meow!"`.

Create instances of both `Dog` and `Cat` and print the sounds they make.

---

### Question 3: Encapsulation
**Q3.** Create a class `BankAccount` that has the following private attributes:
- `balance`: an integer to represent the current balance (initialized to 0).

Implement the following methods:
- `deposit(amount)`: Adds the given amount to the balance.
- `withdraw(amount)`: Deducts the amount from the balance if sufficient, otherwise prints `"Insufficient funds."`.
- `get_balance()`: Returns the current balance.

---

### Question 4: Polymorphism
**Q4.** Create a base class `Shape` with a method `area()`. Then create two subclasses:
- `Rectangle`, with attributes `width` and `height` and an overridden `area()` method that returns the area of the rectangle.
- `Circle`, with attribute `radius` and an overridden `area()` method that returns the area of the circle.

Write a function `print_area(shape)` that takes an object of type `Shape` and prints its area.

---

### Question 5: OOP in Deep Learning
**Q5.** Implement a class `SimpleNeuralNetwork` that has:
- A private attribute `weights`, which is a list of 3 numbers `[0.5, 1.0, 1.5]`.
- A method `forward(input_data)` which returns the result of multiplying the input data by each of the weights, simulating a forward pass in a simple neural network.

Then, initialize the network and pass the input `10` through the `forward()` method, printing the result.
