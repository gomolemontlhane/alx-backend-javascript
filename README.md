# ALX Backend JavaScript

## Overview

This repository contains comprehensive JavaScript and TypeScript backend projects covering modern JavaScript development, asynchronous programming, object-oriented design, data manipulation, and Node.js server development. The projects progress from ES6 fundamentals through advanced backend server implementation and testing practices.

## Repository Structure

The repository is organized into 6 progressive JavaScript/TypeScript backend projects:

### Core Projects

| # | Project | Description | Key Concepts |
|---|---------|-------------|---------------|
| [0x01](#0x01---es6-promises) | ES6 Promises | Master Promise handling and async/await patterns | Promises, Async/Await, Error Handling |
| [0x02](#0x02---es6-classes) | ES6 Classes | Learn OOP with ES6 class syntax and inheritance | Classes, Inheritance, Static Methods |
| [0x03](#0x03---es6-data-manipulation) | ES6 Data Manipulation | Work with arrays, sets, maps, and data structures | Array Methods, Sets, Maps, Reduce |
| [0x04](#0x04---typescript) | TypeScript | Static typing with TypeScript | Type Safety, Interfaces, Generics |
| [0x05](#0x05---nodejs-basic) | Node.js Basic | Build HTTP servers and work with file systems | Express, HTTP, File I/O, Streams |
| [0x06](#0x06---unit-tests-in-js) | Unit Tests in JS | Write comprehensive test suites | Mocha, Chai, Test-Driven Development |

---

## Project Details

### 0x01 - ES6 Promises

**Problem:** Master Promise-based asynchronous programming and modern async/await patterns.

**Key Concepts:**
- Creating and consuming Promises
- Promise chaining
- Async/await syntax
- Error handling with try/catch
- Promise.all() and Promise.race()
- Handling rejected promises

**Topics Covered:**
- Resolving and rejecting promises
- Promise composition
- Async function declarations
- Error propagation

[View Project](./0x01-ES6_promise)

### 0x02 - ES6 Classes

**Problem:** Learn Object-Oriented Programming using ES6 class syntax and implement inheritance patterns.

**Key Concepts:**
- Class declaration and constructor
- Instance and static methods
- Inheritance with extends keyword
- Super keyword usage
- Method overriding
- Getters and setters

**Topics Covered:**
- Class properties and methods
- Constructor functions
- Class inheritance
- Static properties and methods
- Private properties (with underscore convention)

[View Project](./0x02-ES6_classes)

### 0x03 - ES6 Data Manipulation

**Problem:** Master ES6 data structures and functional programming concepts for data transformation.

**Key Concepts:**
- Array methods (map, filter, reduce, forEach)
- Set and Map data structures
- Destructuring assignments
- Spread operator
- Filtering and sorting
- Functional programming paradigm

**Topics Covered:**
- Working with arrays and their methods
- Set operations
- Map key-value pairs
- Array manipulation patterns
- Data transformation techniques

[View Project](./0x03-ES6_data_manipulation)

### 0x04 - TypeScript

**Problem:** Write type-safe JavaScript applications using TypeScript with interfaces, types, and generics.

**Key Concepts:**
- Type annotations
- Interfaces and types
- Generics and constraints
- Enums
- Access modifiers (public, private, protected)
- Modules and namespaces

**Architecture:**
- Task-based organization
- Webpack configuration for bundling
- tsconfig.json for compilation settings
- Type-safe implementations

[View Project](./0x04-TypeScript)

### 0x05 - Node.js Basic

**Problem:** Build production-ready HTTP servers and master Node.js core modules.

**Key Concepts:**
- HTTP server creation
- Request/response handling
- File system operations
- Streams and piping
- Express.js framework
- Routing and middleware

**Architecture:**
- full_server/ - Complete HTTP server implementation
- Express.js application setup
- Route handling
- Static file serving
- Request parsing and responses

[View Project](./0x05-Node_JS_basic)

### 0x06 - Unit Tests in JS

**Problem:** Write comprehensive unit tests and practice Test-Driven Development (TDD).

**Key Concepts:**
- Mocha test framework
- Chai assertion library
- Test structure and organization
- Testing async code
- Mocking and stubbing
- Code coverage

**Testing Patterns:**
- Unit test writing
- Integration testing
- Assertion methods
- Error testing
- Test organization

[View Project](./0x06-unittests_in_js)

---

## Technology Stack

### Core Technologies
- **JavaScript (ES6+)** - Modern JavaScript features
- **TypeScript** - Static type checking
- **Node.js** - JavaScript runtime
- **npm** - Package management

### Frameworks & Libraries
- **Express.js** - Web application framework
- **Mocha** - Testing framework
- **Chai** - Assertion library
- **Webpack** - Module bundler

### Development Tools
- **ESLint** - JavaScript linting (.eslintrc.js)
- **Babel** - JavaScript transpiler
- **.gitignore** - Git configuration

## Learning Outcomes

By working through these projects, you will:

✓ Master ES6 and modern JavaScript syntax and features  
✓ Understand asynchronous programming with Promises and async/await  
✓ Implement OOP patterns using ES6 classes  
✓ Work with advanced data structures (Set, Map, Arrays)  
✓ Build type-safe applications with TypeScript  
✓ Create full-stack HTTP servers with Express.js  
✓ Handle file operations and streams in Node.js  
✓ Write comprehensive unit tests with Mocha and Chai  
✓ Understand test-driven development (TDD) practices  
✓ Configure build tools like Webpack and Babel  

## Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
- Code editor (VS Code recommended)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/gomolemontlhane/alx-backend-javascript.git
   cd alx-backend-javascript
   ```

2. Navigate to a specific project:
   ```bash
   cd 0x01-ES6_promise
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Run the project:
   ```bash
   npm start
   # or
   node main.js
   ```

5. Run tests (for projects with tests):
   ```bash
   npm test
   ```

## Project Structure (Per Project)

Each project directory typically contains:

- **.eslintrc.js** - ESLint configuration
- **package.json** - Project dependencies and scripts
- **tsconfig.json** - TypeScript configuration (if applicable)
- **webpack.config.js** - Webpack bundler configuration (if applicable)
- **Main implementation files** - .js or .ts files with code
- **Test files** - Test suites for validation
- **README.md** - Detailed project documentation

## Common Development Workflows

### Running a Project
```bash
cd 0x02-ES6_classes
node 0-main.js
```

### Running Tests
```bash
npm test
# or with Mocha
mocha tests/
```

### Building with Webpack
```bash
npm run build
# or
webpack
```

### Linting Code
```bash
npm run lint
# or
eslint *.js
```

## JavaScript Concepts Covered

### ES6+ Features
- Arrow functions
- Template literals
- Destructuring
- Spread operator
- Default parameters
- Classes and inheritance
- Promises and async/await

### Functional Programming
- Higher-order functions
- Map, filter, reduce
- Function composition
- Closures
- Pure functions

### Asynchronous Programming
- Callbacks
- Promises
- Async/await
- Error handling
- Promise chains

### Object-Oriented Programming
- Class design
- Inheritance patterns
- Encapsulation
- Polymorphism
- Static and instance methods

## Resources

### JavaScript Learning
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [JavaScript.info - Modern JavaScript](https://javascript.info/)
- [ES6 Features](https://github.com/lukehoban/es6features)

### TypeScript
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [TypeScript Playground](https://www.typescriptlang.org/play)

### Node.js & Express
- [Node.js Official Documentation](https://nodejs.org/docs/)
- [Express.js Guide](https://expressjs.com/)
- [Node.js Best Practices](https://github.com/goldbergyoni/nodebestpractices)

### Testing
- [Mocha Documentation](https://mochajs.org/)
- [Chai Assertion Library](https://www.chaijs.com/)
- [Testing JavaScript](https://testingjavascript.com/)

### Build Tools
- [Webpack Documentation](https://webpack.js.org/)
- [Babel Documentation](https://babeljs.io/)
- [ESLint Guide](https://eslint.org/docs/)

## Contributing

Contributions are welcome! Feel free to:

- Improve existing implementations
- Add alternative approaches
- Enhance documentation
- Add more test cases
- Report bugs or issues
- Suggest performance optimizations

## Best Practices

### Code Quality
- Follow ESLint configuration rules
- Use meaningful variable names
- Comment complex logic
- Keep functions small and focused
- Use async/await instead of callbacks

### Performance
- Use appropriate data structures (Arrays, Sets, Maps)
- Implement efficient algorithms
- Minimize synchronous operations
- Use streams for large file operations

### Testing
- Write tests for all functionality
- Aim for high code coverage
- Test edge cases and error conditions
- Use descriptive test names

## Project Progression

The projects are designed to build upon each other:

1. **0x01** - Learn async patterns (foundation)
2. **0x02** - Learn OOP (complementary)
3. **0x03** - Master data structures (intermediate)
4. **0x04** - Add type safety (advanced)
5. **0x05** - Build real servers (practical)
6. **0x06** - Ensure quality with tests (polish)

## Author

**Gomolemo Ntlhane**

- GitHub: [@gomolemontlhane](https://github.com/gomolemontlhane)
- Focus: JavaScript/TypeScript backend development, modern practices

## License

This project is part of the ALX Software Engineering program curriculum.

---

## Quick Reference

### ES6 Promise Methods

| Method | Purpose |
|--------|----------|
| `Promise.resolve()` | Return resolved promise |
| `Promise.reject()` | Return rejected promise |
| `Promise.all()` | All promises settle |
| `Promise.race()` | First promise settles |
| `async/await` | Syntactic sugar for promises |

### Array Methods

| Method | Returns | Use Case |
|--------|---------|----------|
| `map()` | New array | Transform elements |
| `filter()` | New array | Select elements |
| `reduce()` | Single value | Accumulate values |
| `forEach()` | undefined | Side effects |
| `find()` | First match | Find element |

### Node.js Core Modules

| Module | Purpose |
|--------|----------|
| `fs` | File system operations |
| `http` | HTTP server/client |
| `path` | Path utilities |
| `stream` | Streaming data |
| `events` | Event emitter |

---

**Last Updated:** 2025  
**Status:** Active Development  
**Difficulty:** Beginner to Intermediate
