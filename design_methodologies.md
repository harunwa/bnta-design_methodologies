## Software Design Methodologies
### Coupling and Cohesion in Structured Design

**Coupling** refers to how tightly components in a system are interconnected. In structural design, low coupling is preffered as it means components are more independent, making it is easier to modify or replace them without affecting others.

**Cohesion** reflects how closely related the elements within a module are. High cohesion suggests that elements work together towards a common goal or task within the module.

### Different Approaches: Top-down vs Bottom-up

**Top-down design** begins with the overall structure and breaks it down into smaller components. It's like starting with the big picture and then refining the details.

**Bottom-up design** starts with individual elements and gradually builds them up into larger structures. It's able to assemble small pieces to form a bigger picture.

**Function-oriented design** aligns better with a bottom-up approach as it involves breaking down functionalities into smaller, more manageable functions.

### Class Diagrams in Object-Oriented Design

**Class diagrams** are more useful in object-oriented design. They visually represent the classes, their attributes, methods, and relationships, serving as a roadmap for how the system's components interact with each other.

### The four pillars of Object-Oriented Programming

**1. Encapsulation:** This involves bundling data and methods together within a class, shielding the data from outside interference while allowing controlled access through methods.

**2. Inheritance:** This allows classes to inherit properties and behaviours from other classes, fostering code reuse.

**3. Polymorphism:** This is the ability for objects of different classes to be treated as objects of a common superclass, promoting flexibility and facilitating the implementation of complex behaviours.

**4. Abstraction:** This involves focusing on essential qualities while hiding unnecessary details, providing a simplified view of objects and their interactions.

### Understanding Strategy Pattern

- The strategy pattern is a method for defining a family of algorithms, encapsulating each one, and making them interchangeable. It allows for flexible switching between algorithms without modifying the client code.

- In functional programming, the strategy pattern might involve passing functions as arguments or employing higher-order functions.

- In object-oriented programming, it typically entails defining interchangeable algorithm objects that can be used dynamically by the client.

### Recommendation for the New Online Payment System

For the new online payment system aiming for widespread adoption across various sectors, I would recommend adopting the object-oriented design methodology. Here's why:

**Flexibility:** Object oriented design provides the flexibility needed to accommodate diverse requirements across different sectors without being tied to a specific domain.

**Reusability:** By promoting code reuse through inheritance and composition, object-oriented design allows for utilising common functionalities across sectors without duplicating code. 

**Maintainability:** The modular structure of object-oriented design enhances maintainability by facilitating changes to specific components without disrupting the entire system, crucial for adapting to evolving business needs.

**Scalability:** Object-oriented design enables the system to evolve over time to meet changing market demands and incorporate new features without major architectural changes.

Overall, object-oriented design offers the necessary flexibility, reusability, maintainability, and scalability required for a versatile online payment system targeting diverse market sectors.