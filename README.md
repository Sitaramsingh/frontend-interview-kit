# frontend-interview-kit
A curated frontend learning and interview preparation kit covering JavaScript, React, Next.js, performance, and frontend system design.

This repository is designed to:
- Build strong frontend fundamentals
- Serve as a long-term learning reference
- Help prepare for frontend interviews at all levels



## 📚 Table of Contents

- [Quick Start](#quick-start)
<!-- - [Curriculum Overview](#curriculum-overview) -->
<!-- - [Fundamentals: HTML & CSS](#fundamentals-html--css) -->
- [JavaScript Core](#javascript-core)
- [JavaScript Advance](#javascript-advance)
- [React & Modern Frameworks](#react--modern-frameworks)
- [Next js](#nextjs--modern-frameworks)
- [Design Patterns (JavaScript & React)](#design-patterns-javascript--react)
<!-- - [Data Structures & Algorithms](#data-structures--algorithms) -->
- [Frontend System Design](#frontend-system-design)
- [Testing & QA](#testing--qa)
- [Accessibility (a11y)](#accessibility-a11y)
- [Performance & Web Vitals](#performance--web-vitals)
- [Tooling, Build & Deploy](#tooling-build--deploy)
- [Machine Coding Rounds](#machine-coding-rounds)
- [Bonus: Frontend with AI](#bonus-frontend-with-ai)
- [Communication & Technical Leadership](#communication--technical-leadership)
- [Interview Kit](#interview-kit)
- [Projects & Build List](#projects--build-list)
- [Contribution & Community](#contribution--community)
- [Appendix](#appendix)
- [License](#license)


## 🚀 Quick Start
Coming soon...

## JavaScript  – Study Timetable

| Day | Topics | Focus | Estimated Time |
|----|------|------|----------------|
| Day 1 | Execution Context & Call Stack<br/>Hoisting & Temporal Dead Zone | Understand how JavaScript executes code and handles variable declarations | 1.5–2 hrs |
| Day 2 | Scope, Closures & Lexical Environment | Master closures and lexical scoping with real-world examples | 2 hrs |
| Day 3 | `this` Keyword & Binding<br/>Equality & Edge Cases | Avoid common `this` pitfalls and tricky comparisons | 1.5–2 hrs |
| Day 4 | Data Types & Type Coercion<br/>Shallow vs Deep Copy | Predict JavaScript behavior and handle object copying safely | 1.5 hrs |
| Day 5 | Arrays & Core Methods<br/>Functional Programming Basics | Write clean, predictable, and functional-style JavaScript | 1.5–2 hrs |
| Day 6 | Revision | Review Week 1 concepts and identify weak areas | 1 hr |
| Day 7 | Asynchronous JavaScript | Understand callbacks, promises, and async/await | 2 hrs |
| Day 8 | Event Loop | Learn execution order, microtasks, and macrotasks | 1.5 hrs |
| Day 9 | Timers & Browser APIs | Work confidently with timers and browser APIs | 1–1.5 hrs |
| Day 10 | Memory Management & Garbage Collection | Prevent memory leaks and understand JS memory lifecycle | 1.5 hrs |
| Day 11 | Objects, Prototypes & Inheritance | Deep dive into prototype chain and inheritance | 1.5–2 hrs |
| Day 12 | Revision | Review async, memory, and prototype concepts | 1 hr |
| Day 13 | ES6+ Features<br/>Modules & Bundling Basics | Use modern JavaScript features and understand modules | 1.5 hrs |
| Day 14 | Error Handling & Debugging<br/>Immutability & State Updates | Build resilient code and manage state safely | 1.5–2 hrs |
| Day 15 | Security Basics (Frontend)<br/>Performance Fundamentals | Understand frontend security risks and performance basics | 1–1.5 hrs |
| Day 16–18 | Final Revision & Practice | Revise all topics and prepare interview explanations | Flexible |


 ## JavaScript Core

A curated list of core JavaScript topics with recommended learning resources.  
These concepts form the foundation for modern frontend development and frontend interviews.

### 📘 Primary Learning Resource
- **javascript.info** – https://javascript.info/  
  A comprehensive and beginner-to-advanced JavaScript reference.  
  Contributors are encouraged to prefer this resource when adding new topics.

### Execution Context & Call Stack
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Execution_context
- Learn: https://www.youtube.com/watch?v=exrc_rLj5iw  
> Focus: How JavaScript creates execution contexts and manages function calls.

### Hoisting & Temporal Dead Zone
- Learn: https://developer.mozilla.org/en-US/docs/Glossary/Hoisting
- Learn: https://javascript.info/var  
> Focus: Difference between `var`, `let`, and `const` and variable access timing.

### Scope, Closures & Lexical Environment
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
- Learn: https://javascript.info/closure  
> Focus: How closures retain access to outer scope and real-world use cases.

### `this` Keyword & Binding
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
- Learn: https://javascript.info/object-methods  
> Focus: Behavior of `this` in functions, arrow functions, and classes.

### Data Types & Type Coercion
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
- Learn: https://javascript.info/type-conversions  
> Focus: Primitive vs non-primitive data types and implicit conversions.

### Asynchronous JavaScript
- Learn: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous
- Learn: https://javascript.info/async  
> Focus: Callbacks, Promises, async/await, and async error handling.

### Event Loop
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Event_loop
- Learn: https://www.youtube.com/watch?v=8aGhZQkoFbQ  
> Focus: Execution order of synchronous code, microtasks, and macrotasks.

### Memory Management & Garbage Collection
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management
- Learn: https://javascript.info/garbage-collection  
> Focus: Memory allocation and common causes of memory leaks.

### Objects, Prototypes & Inheritance
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain
- Learn: https://javascript.info/prototype-inheritance  
> Focus: Prototype chain and how JavaScript implements inheritance.

### Arrays & Core Methods
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
- Learn: https://javascript.info/array-methods  
> Focus: Common array methods and mutating vs non-mutating operations.

### ES6+ Features
- Learn: https://javascript.info/es6
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules  
> Focus: Modern JavaScript syntax used in everyday frontend development.

### Error Handling & Debugging
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch
- Learn: https://javascript.info/try-catch  
> Focus: Handling runtime errors and debugging async code.

### Immutability & State Updates
- Learn: https://redux.js.org/usage/structuring-reducers/immutable-update-patterns
- Learn: https://javascript.info/object-copy  
> Focus: Why immutability matters in React and state management.

### Shallow vs Deep Copy
- Learn: https://developer.mozilla.org/en-US/docs/Glossary/Shallow_copy
- Learn: https://javascript.info/object-copy  
> Focus: Copying objects safely and avoiding reference-related bugs.

### Equality & Edge Cases
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness
- Learn: https://javascript.info/comparison  
> Focus: `==` vs `===`, `Object.is`, and tricky comparison cases.

### Functional Programming Basics
- Learn: https://javascript.info/functional-programming
- Learn: https://www.freecodecamp.org/news/functional-programming-in-javascript/  
> Focus: Pure functions, immutability, and predictable code.

### Timers & Browser APIs
- Learn: https://developer.mozilla.org/en-US/docs/Web/API/setTimeout
- Learn: https://javascript.info/settimeout-setinterval  
> Focus: Timers, delays, and browser-provided APIs.

### Modules & Bundling Basics
- Learn: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules
- Learn: https://javascript.info/modules-intro  
> Focus: ES modules, imports/exports, and bundling fundamentals.

### Security Basics (Frontend)
- Learn: https://developer.mozilla.org/en-US/docs/Web/Security
- Learn: https://web.dev/security/  
> Focus: XSS risks and safe DOM manipulation practices.

### Performance Fundamentals
- Learn: https://developer.mozilla.org/en-US/docs/Learn/Performance
- Learn: https://web.dev/fast/  
> Focus: Main-thread blocking, expensive operations, and basic performance optimizations.



## ⚛️ React & Modern Frameworks
Coming soon...

## ⚛️ Next js & Modern Frameworks
Coming soon...
