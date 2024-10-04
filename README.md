# Python Warm-Up Exercises

The `warm-up.ipynb` notebook contains a few warm-up tasks covering fundamental concepts in Python intended to help practice basic skills and serve as a foundation for more advanced coding.

# Extended Core Principles for Python Code Organization

| **Principle**       | **Description**                               | **Python Concept/Action**                                  | **Example Code Snippet**                                        |
|---------------------|----------------------------------------------|------------------------------------------------------------|-----------------------------------------------------------------|
| **Read**            | Retrieve or load data                        | File I/O, Database Access, API Calls                       | `with open(filepath, 'r') as f: data = json.load(f)`           |
| **Validate**        | Ensure data is consistent and correct        | Data Validation, Type Checking                             | `if not isinstance(data, dict): raise ValueError("Invalid")`   |
| **Process**         | Transform or modify data                     | Functions, List Comprehensions, Data Processing Libraries  | `processed_data = [item * 2 for item in data if item > 0]`     |
| **Write**           | Save or export data                          | File Writing, Database Insertions                          | `with open(filepath, 'w') as f: json.dump(data, f)`            |
| **Abstract**        | Encapsulate complexity and reuse logic       | Classes, Modules, Functions                                | `class DataHandler: def read(): ... def write(): ...`          |
| **Orchestrate**     | Coordinate the flow of actions               | Pipelines, Workflows, Function Composition                 | `def pipeline(): read(); validate(); process(); write()`       |
| **Extend**          | Enable future extensions or additions        | Inheritance, Plug-ins, Strategy Patterns                   | `def custom_process(data, func): return func(data)`            |
| **Modularize**      | Break code into manageable modules           | Packages, Imports, Modules                                 | `import data_processing_module`                                |
| **Encapsulate**     | Keep details hidden and expose only what's needed | OOP: Private Attributes, Accessors                         | `class Car: def __init__(self): self.__engine = 'V8'`         |
| **Polymorph**       | Handle different objects through the same interface | Polymorphism, Duck Typing                                  | `def drive(vehicle): vehicle.accelerate()`                     |
| **Compose**         | Use simpler objects to build more complex ones | Composition over Inheritance                               | `class Engine: ... class Car: def __init__(self): self.engine = Engine()` |
| **Isolate**         | Separate concerns for better testability     | Dependency Injection, Interfaces                           | `def calculate_sum(data_loader): data = data_loader.load()`    |
| **Iterate**         | Work with collections of items               | Iterators, Generators                                      | `for item in data: ...`                                        |
| **Delegate**        | Assign responsibility to different components| Design Patterns (Command, Delegation)                      | `class Logger: def log(message): print(message)`               |
| **Guard**           | Ensure boundaries and proper state           | Context Managers, Pre/Post-conditions                      | `with db_transaction() as session: ...`                        |
| **Reuse**           | Avoid code duplication and improve maintainability | Functions, Libraries, Mixins                               | `def common_function(): ...`                                   |
