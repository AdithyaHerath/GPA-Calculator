# University GPA Calculator

A simple, user-friendly web application to calculate your GPA for the BSc (Hons) Computer Science program at Plymouth University.

## Features

- Pre-loaded with all BSc Computer Science subjects and their credit values
- Organized by semester for easy navigation
- Real-time GPA calculation as you select grades
- Automatically updates results without needing to click a button
- Shows degree classification based on your GPA
- Clean, modern user interface that works on all devices

## How to Use

1. Open `index.html` in any web browser
2. Select grades for your subjects using the dropdown menus
3. GPA and classification will update automatically as you select grades
4. Use "Reset All" if you want to clear all grades and start over

## GPA Calculation

The GPA is calculated using the university's grading scale:

- A+ = 90–100 marks (GPA 4.0)
- A = 85–89 marks (GPA 4.0)
- A- = 80–84 marks (GPA 3.7)
- B+ = 75–79 marks (GPA 3.3)
- B = 70–74 marks (GPA 3.0)
- B- = 65–69 marks (GPA 2.7)
- C+ = 60–64 marks (GPA 2.3)
- C = 55–59 marks (GPA 2.0)
- C- = 50–54 marks (GPA 1.7)
- D+ = 40–49 marks (GPA 1.3)
- D = 30–39 marks (GPA 1.0)
- E = 00–29 marks (GPA 0.0)

The formula used is:
```
GPA = ∑(Grade Points × Credit Hours) / ∑Credit Hours
```

Where:
- Total Grade Points = Sum of (Credit Hours × Grade Points) for each subject
- Total Credit Hours = Sum of Credit Hours for all subjects with grades assigned

## Degree Classifications

The calculator shows your degree classification based on the following criteria:

- **First Class Honours:** GPA of 3.70 or above
- **Second Class (Upper Division) Honours:** GPA of 3.30 or above
- **Second Class (Lower Division) Honours:** GPA of 3.00 or above
- **Pass:** GPA of 2.00 or above
- **Fail:** GPA below 2.00

## BSc Computer Science Program Details

This calculator includes the following subjects from the BSc (Hons) Computer Science program at Plymouth University:

### Semester 1
- CS101.3 - Introduction to Computer Science (3 credits)
- MA101.3 - Mathematics for Computing (3 credits)
- CS102.3 - Programming Fundamentals (3 credits)
- CS103.2 - Personal Development (2 credits)
- EL101.1 - Academic Writing and Communication (1 credit)
- CS105.3 - Database Management Systems (3 credits)

### Semester 2
- CS106.3 - Algorithms and Data Structures (3 credits)
- CS104.3 - Computer Architecture (3 credits)
- SE102.3 - Web Based Application Development (3 credits)
- SE103.3 - Systems Analysis and Design (3 credits)
- CS107.3 - Object Oriented Programming with C# (3 credits)

## Author

© 2025 [Adithya Herath](https://github.com/AdithyaHerath). All rights reserved. 