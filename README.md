# FEM - Practical Web App Patterns with Vanilla JS Course by Max Firtman

- [FEM - Practical Web App Patterns with Vanilla JS Course by Max Firtman](#fem---practical-web-app-patterns-with-vanilla-js-course-by-max-firtman)
  - [Lessons](#lessons)
  - [Notes](#notes)
    - [Lesson 01 - Introduction](#lesson-01---introduction)
    - [Lesson 02 - Design Patterns](#lesson-02---design-patterns)
    - [Lesson 03 - Components of a Design](#lesson-03---components-of-a-design)
    - [Lesson 04 - Design Patterns for VanillaJS Web Apps](#lesson-04---design-patterns-for-vanillajs-web-apps)
    - [Lesson 05 - Classic Patterns](#lesson-05---classic-patterns)
    - [Lesson 06 - Singleton \& Factory Patterns](#lesson-06---singleton--factory-patterns)
    - [Lesson 07 - Decorator Pattern](#lesson-07---decorator-pattern)
    - [Lesson 08 - Adapter, Mixin, \& Value Object Patterns](#lesson-08---adapter-mixin--value-object-patterns)
    - [Lesson 09 - Observer \& Template Method Patterns](#lesson-09---observer--template-method-patterns)
    - [Lesson 10 - Memento \& Command Patterns](#lesson-10---memento--command-patterns)
    - [Lesson 11 - Todo Masters Project Setup](#lesson-11---todo-masters-project-setup)

## Lessons

- [x] ~~_Lesson 01 - Introduction_~~ [2024-11-07]
- [x] ~~_Lesson 02 - Design Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 03 - Components of a Design_~~ [2024-11-07]
- [x] ~~_Lesson 04 - Design Patterns for VanillaJS Web Apps_~~ [2024-11-07]
- [x] ~~_Lesson 05 - Classic Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 06 - Singleton & Factory Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 07 - Decorator Pattern_~~ [2024-11-07]
- [x] ~~_Lesson 08 - Adapter, Mixin, & Value Object Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 09 - Observer & Template Method Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 10 - Memento & Command Patterns_~~ [2024-11-07]
- [x] ~~_Lesson 11 - Todo Masters Project Setup_~~ [2024-11-11]
- [x] ~~_Lesson 12 - ECMAScript Modules & globalThis_~~ [2024-11-11]
- [x] ~~_Lesson 13 - Observer Pattern with Mixins_~~ [2024-11-11]
- [x] ~~_Lesson 14 - Creating Data Classes_~~ [2024-11-11]
- [ ] Lesson 15 - Adding TodoList Methods
- [ ] Lesson 16 - Add & Delete Commands
- [ ] Lesson 17 - Rendering TodoList Items
- [ ] Lesson 18 - Saving Todos in LocalStorage
- [ ] Lesson 19 - Adding Keyboard Shortcuts
- [ ] Lesson 20 - Undo with Memento Pattern
- [ ] Lesson 21 - Single Page Application Patterns
- [ ] Lesson 22 - Coffee Masters Project Tour
- [ ] Lesson 23 - Lazy Loading JavaScript Components
- [ ] Lesson 24 - View Transitions
- [ ] Lesson 25 - Morphing Elements Between Pages
- [ ] Lesson 26 - HTML Template Interpolation
- [ ] Lesson 27 - Routing Metadata
- [ ] Lesson 28 - Multi-Page Application Patterns
- [ ] Lesson 29 - Cooking Masters Project Tour
- [ ] Lesson 30 - Prefetch & Prerender
- [ ] Lesson 31 - Promisify, Flux & Redux Patterns
- [ ] Lesson 32 - Lazy Sync, Proxy & Middleware Patterns
- [ ] Lesson 33 - Advanced Ideas
- [ ] Lesson 34 - Wrapping Up

## Notes

### Lesson 01 - Introduction

- Run a local web server:
  - `npx serve -s`

### Lesson 02 - Design Patterns

- Design Patterns are reusable solutions to common software design problems. They provide a blueprint for how to structure and solve problems in software development. Design patterns are often used to improve code quality, maintainability, and scalability and help to create a common vocabulary.
- References Gang of Four Book
  - Erich Gamma
  - Richard Helm
  - Ralph Johnson
  - John Vlissides
  - Published 1994

### Lesson 03 - Components of a Design

- Elements of a Design Pattern
  - 1. **Name**
  - 2. **Problem** it means to solve
  - 3. Propose **solution**
  - 4. **Context** or scope when it is used
  - 5. **Consequences** of proposed solutions (pros/cons)
  - 6. **Examples** i.e. how it is used

### Lesson 04 - Design Patterns for VanillaJS Web Apps

- Nothing to note

### Lesson 05 - Classic Patterns

- Classic Design Patterns
  - 1. Creational
  - 2. Structural
  - 3. Behavioral

### Lesson 06 - Singleton & Factory Patterns

- **Two Creation Patterns:**
- **Singleton Pattern**

  - Ensure that the class only has one instance
  - Provide a global point of access to said instance
  - Use Cases:
    - Managing a global configuration object
    - Database connection pooling
    - Logging service
    - State management

- **Factory Pattern**
  - Reduce complexity in object creation
    - Multiple steps, conditional logic, dependencies
  - Use Cases:
    - UI element creation
    - Different type of notifications
    - Data parsers

### Lesson 07 - Decorator Pattern

- **Structural Pattern**
  - Solutions for composing classes and objects to form larger structures while keeping them flexible and efficient
  - Simply relationships between entities to ensure system maintainability and scalability
- **Decorator Patterns**
  - React HOC use the decorator pattern
  - Need to add functionality to objects dynamically without modifying the structure
  - Wrap an object with another object that adds desired behavior
  - USE CASES:
    - Add logging, validation, or caching to method calls
    - Extending UI elements with additional features
    - Wrapping API responses to format or process data before passing it on

### Lesson 08 - Adapter, Mixin, & Value Object Patterns

- **Adapter Pattern**
  - Allow incompatible interfaces to work together
  - USE CASES:
    - Integrating 3rd-party libraries with different interfaces into your application
    - Adapting legacy code to work with new systems
    - Converting data formats
- **Mixin Pattern**
  - Share functionality between classes without using inheritance
- **Value Object Pattern**
  - 1. **Definition**: A value object is an object that represents a single value and does not have any state or behavior. It is immutable and can be used as a key in a map or set.
  - 2. **Use Cases**: When you need to represent a single value that does not have any state or behavior, such as a date, a currency, or a size.

### Lesson 09 - Observer & Template Method Patterns

- **Behavioral Pattern**
  - Deal with object interaction and responsibility distribution. Focus on how objects interact to ensure system remains flexible and easy to extend
- **Observer Pattern**
  - Enable _Subject_ objects to notify _Observer_ objects about changes in state without requiring them to be tightly coupled
  - USE CASES:
    - Event handlers
    - Real-time notifications
    - UI updates
- **Template Method Pattern**
  - Define a skeleton of an algorithm that will change on different implementations
  - USE CASE:
    - Form Validation
    - Sorting Algorithms

### Lesson 10 - Memento & Command Patterns

- **Memento Pattern**
  - Capture and externalize the state of an object without violating encapsulation
  - Create an object that captures the state of the original object and provide methods to save and restore the state
  - USE CASES:
    - Undo/Redo functionality
    - Saving a game or app session
    - Time travel debugging
- **Command Pattern**
  - How to avoid hard-wiring a request from its invoker
  - Create an object that is used to encapsulate all information to perform an action at later time

### Lesson 11 - Todo Masters Project Setup

- Problems with initial implementation:
  - How to save list locally?
  - Add keyboard shortcuts
  - Make it more complex in the future
  - Create an undo action
  -
