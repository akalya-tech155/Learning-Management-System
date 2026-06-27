# Learning Management System (LMS)

## Professional Title
Online Training & Certification Portal

## Project Overview

This project is an end-to-end Playwright automation framework developed using TypeScript and the Page Object Model (POM). It automates the major functionalities of a Learning Management System (LMS), including student registration, course enrollment, assessments, and certificate generation.

## Tech Stack

- Playwright
- TypeScript
- Node.js
- Page Object Model (POM)
- Git & GitHub
- Visual Studio Code

## Project Structure

```
Learning-Management-System/
│
├── pages/
│   ├── LoginPage.ts
│   ├── StudentRegistrationPage.ts
│   ├── CourseCatalogPage.ts
│   ├── EnrollmentPage.ts
│   ├── AssessmentPage.ts
│   └── CertificatePage.ts
│
├── tests/
│   ├── login.spec.ts
│   ├── studentRegistration.spec.ts
│   ├── courseCatalog.spec.ts
│   ├── enrollment.spec.ts
│   ├── assessment.spec.ts
│   └── certificate.spec.ts
│
├── playwright.config.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Modules

### Student Registration
- Register a new student
- Validate mandatory fields
- Validate email format
- Prevent duplicate registration
- Verify successful registration

### Course Catalog
- Search available courses
- Filter courses
- View course details
- Verify instructor information
- Verify course duration

### Enrollment Module
- Enroll in a course
- Prevent duplicate enrollment
- Verify enrolled courses
- Cancel enrollment

### Assessment Module
- Start assessment
- Answer questions
- Submit assessment
- Verify score
- Verify pass/fail status

### Certificate Generation
- Verify certificate availability
- Generate certificate
- Verify student name
- Verify course name
- Verify issue date
- Download certificate

## Git Branches

- main
- student-registration
- course-catalog
- enrollment-module
- assessment-module
- certificate-generation

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
npm install
```

Install Playwright browsers:

```bash
npx playwright install
```

## Running the Tests

Run all tests:

```bash
npx playwright test
```

Run a specific test:

```bash
npx playwright test tests/studentRegistration.spec.ts
```

Run tests in headed mode:

```bash
npx playwright test --headed
```

Open the HTML report:

```bash
npx playwright show-report
```

## Framework Design

- Page Object Model (POM)
- Reusable page methods
- Organized test structure
- Easy maintenance and scalability

## Author

**AKALYA**

Automation Test Engineer (Playwright | TypeScript | SQL | API Testing)