
# Car Management System:

## Table of Contents
1. [Features](#features)
2. [OOP Concepts Used](#oop-concepts-used)
3. [Code Structure](#code-structure)
4. [How to Run](#how-to-run)
5. [Example Output](#example-output)
6. [Contributing](#contributing)
7. [License](#license)

---

## Features
- **Vehicle Management**: Create and manage vehicles, cars, and electric cars.
- **OOP Principles**: Demonstrates key OOP concepts like inheritance, encapsulation, polymorphism, and abstraction.
- **Public and Private Methods**: Shows how to use public and private methods effectively.
- **Getter and Setter Methods**: Encapsulates private attributes with getter and setter methods.
- **Static and Class Methods**: Includes examples of static and class methods.
- **Method Overriding and Overloading**: Demonstrates method overriding and simulated method overloading.

---

## OOP Concepts Used
1. **Class**:Blueprint for creating objects.
3. **Object**: Instance of a class.
4. **Attributes**: Variables that belong to an object or class.
5. **Methods**: Functions defined inside a class.
6. **Arguments**: Values passed to methods.
7. **Public Methods**: Accessible from outside the class.
8. **Private Methods**: Accessible only within the class.
9. **Encapsulation**: Bundling data and methods, restricting access to private attributes.
10. **Inheritance**: Creating a new class from an existing class.
11. **Polymorphism**: Methods behaving differently based on the object.
12. **Abstraction**: Hiding complex implementation details.
13. **Constructor**: Special method for initializing objects.
14. **Destructor**: Special method called when an object is destroyed.
15. **Static Methods**: Methods that belong to the class rather than an instance.
16. **Class Methods**: Methods that operate on the class itself.
17. **Instance Variables**: Variables specific to an object.
18. **Class Variables**: Variables shared among all instances of a class.
19. **Getter and Setter Methods**: Methods to access and modify private attributes.
20. **Method Overriding**: Redefining a method in a child class.
21. **Method Overloading**: Simulating multiple methods with the same name but different parameters.

---

## Code Structure
- **Vehicle (Abstract Class)**:
  - Defines a blueprint for vehicles.
  - Contains an abstract method `display_info`.
- **Car (Parent Class)**:
  - Inherits from `Vehicle`.
  - Implements `display_info`.
  - Includes private attributes, public/private methods, getters/setters, static/class methods, and a destructor.
- **ElectricCar (Child Class)**:
  - Inherits from `Car`.
  - Overrides `display_info`.
  - Simulates method overloading in the `charge` method.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-management-oop.git
Navigate to the project directory:

bash
Copy
cd car-management-oop
Run the Python script:

bash
Copy
python main.py
Example Output
Copy
Toyota Corolla (2020)
Tesla Model S (Electric, 2022)
Corolla
Camry
Engine status: OK
Engine started!
True
4
Charging Tesla Model S for 2 hours.
Charging Tesla Model S with fast charge for 1 hours.
Toyota Camry is being destroyed.
Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a pull request.
