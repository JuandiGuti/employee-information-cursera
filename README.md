# Employee Management System

A simple web application built with **HTML** and **JavaScript** to manage a list of employees.  
It allows displaying, filtering, and calculating totals using DOM manipulation.

## Features

- **Display Employees**: shows all employees.
- **Calculate Total Salaries**: sums all salaries and displays the result in an `alert`.
- **Display HR Employees**: filters employees from the **HR** department.
- **Find Employee by ID**: searches by `id` and displays the result.
- **Find Employees by Specialization**: filters employees by `specialization` (e.g., `JavaScript`).

## Project Structure

```
employee-management-system/
├─ employee_details.html
└─ employee_details.js
```

- `index.html`: page structure and buttons that trigger the functions.
- `employee_details.js`: logic for listing, filtering, and calculations.

## Example Data

```js
const employees = [
  { id: 1, name: 'John Doe', age: 30, department: 'IT', salary: 50000, specialization: 'JavaScript' },
  { id: 2, name: 'Alice Smith', age: 28, department: 'HR', salary: 45000, specialization: 'JavaScript' },
  { id: 3, name: 'Bob Johnson', age: 35, department: 'Finance', salary: 60000, specialization: 'Python' },
];
```

## Usage

1. Open `index.html` in your browser.
2. Click the buttons to execute the functions.
3. Results will be displayed in the `#employeesDetails` container or as an `alert`.

## Main Functions (Summary)

- `displayEmployees()`: renders all employees.
- `calculateTotalSalaries()`: calculates total salaries using `reduce`.
- `displayHREmployees()`: filters by `department === "HR"`.
- `findEmployeeById(employeeId)`: finds an employee using `find`.
- `findEmployeesBySpecialization()`: filters employees by specialization (e.g., `JavaScript`).

## Requirements

- Modern browser with ES6 support.
- No server or external dependencies required.

## Suggested Improvements

- Form to create/edit employees.
- Persistence with `localStorage` or API integration.
- Styling with CSS or a UI framework.
- Validations and advanced search options.
