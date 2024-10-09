# TypeScript Project

## Overview

This project demonstrates the use of TypeScript to build a series of tasks focusing on interfaces, classes, advanced types, and namespaces. It aims to showcase how TypeScript's features can be utilized for better type-checking, cleaner code, and more robust applications.

## Table of Contents

Technologies

## Project Structure

# Tasks

Task 0: Creating an interface for a student
Task 1: Let's build a Teacher interface
Task 2: Extending the Teacher class
Task 3: Printing teachers
Task 4: Writing a class
Task 5: Advanced types Part 1
Task 6: Creating functions specific to employees
Task 7: String literal types
Task 8: Ambient Namespaces
Task 9: Namespace & Declaration merging
Setup Instructions

## Technologies

- TypeScript - A strongly typed programming language that builds on JavaScript.
- Node.js - A runtime environment to execute TypeScript code.
- Webpack - A module bundler for JavaScript applications.
- ESLint - A tool to analyze code for potential issues and enforce coding standards.

# Project Structure

```bash
.
├── task_0
│   ├── js
│   │   └── main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_1
│   ├── js
│   │   └── main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_2
│   ├── js
│   │   └── main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
├── task_3
│   ├── js
│   │   ├── crud.d.ts
│   │   ├── interface.ts
│   │   └── main.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── webpack.config.js
└── task_4
    ├── js
    │   ├── Cpp.ts
    │   ├── Subject.ts
    │   ├── Teacher.ts
    ├── package.json
    ├── tsconfig.json
    └── webpack.config.js
```

## Tasks

Task 0: Creating an interface for a student

- File: `task_0/js/main.ts`
- Description: This task involves creating an interface Student with attributes such as firstName, lastName, age, and location. It also includes rendering this data into a table.

Task 1: Let's build a Teacher interface

- File: `task_1/js/main.ts`
- Description: This task defines a Teacher interface and explores the concept of optional and read-only attributes.

Task 2: Extending the Teacher class

- File: `task_1/js/main.ts`
- Description: We extend the Teacher interface to create a new Directors interface that adds an additional attribute numberOfReports.

Task 3: Printing teachers

- File: `task_1/js/main.ts`
- Description: This task introduces the printTeacher function, which accepts the first name and last name and returns a formatted string.

Task 4: Writing a class

- File: `task_1/js/main.ts`
- Description: A StudentClass is implemented to handle various student-related operations.

Task 5: Advanced types Part 1

- File: `task_2/js/main.ts`
- Description: Advanced typing concepts are introduced, along with the creation of a createEmployee function that handles both Teacher and Director.

Task 6: Creating functions specific to employees

- File: `task_2/js/main.ts`
- Description: Functions like isDirector and executeWork are added, depending on the employee type.

Task 7: String literal types

- File: `task_2/js/main.ts`
- Description: The task adds string literal types to define which subjects can be taught by a teacher, and implements a teachClass function.

Task 8: Ambient Namespaces

- File: `task_3/js/main.ts`
- Description: This task explores the use of ambient namespaces for CRUD operations, along with interfaces for handling data.

Task 9: Namespace & Declaration merging

- File: `task_4/js/Teacher.ts`, `task_4/js/Subject.ts`, `task_4/js/Cpp.ts`
- Description: Declaration merging and the use of namespaces to handle classes like `Cpp` and `Subject`.

# Setup Instructions

## Prerequisites

- Node.js - Make sure Node.js is installed on your system.
- TypeScript - Globally install TypeScript using:

```bash
npm install -g typescript
```

# Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the desired task folder (eg. task 0)

```bash
cd task_0
```

3. Install the dependencies:

```bash
npm install
```

## Running the Project

1. Run the TypeScript compiler:

```bash
npm run build
```

2.Open the `dist/index.html` file in your browser to see the rendered content.
