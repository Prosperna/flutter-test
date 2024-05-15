# P1 Mobile App Development Test

## Introduction

This Requirements outlines the requirements and deliverables for a simple Flutter e-commerce mobile app development test. This test is designed to evaluate the technical skills and problem-solving abilities of candidates applying for a Flutter developer position at Prosperna. The focus is on best practices, Flutter skills, and basic adherence to DevSecOps principles, without advanced concepts.

## Objectives

- **Assess Flutter Skills:** Demonstrate proficiency in Flutter and Dart.
- **UI/UX Design:** Implement user-friendly and visually appealing interfaces.
- **State Management:** Apply basic state management techniques.
- **API Integration:** Integrate and handle RESTful APIs.
- **Adherence to Best Practices:** Follow best practice engineering principles such as the - DRY method, TDD, and separation of concerns.
- **Problem Solving:** Showcase problem-solving skills and coding practices.

## Key Features and Requirements

1. ### User Authentication

- **Description:** Implement basic user authentication.
- **Requirements:**
  - Registration with email and password.
  - Login with email and password.
  - Display appropriate error messages for invalid inputs.
  - Redirect to the home screen after successful login.

2. ### Product Listing

- **Description:** Display a list of products fetched from a REST API.
- **Requirements:**
  - Fetch product data from a public API or a custom endpoint.
  - Display products in a grid or list view.

3. ### Product Details

- **Description:** Show detailed information for a selected product.
- **Requirements:**
  - Display product details in a new screen.
  - Include fields such as title, description, price, and image.
  - Allow users to add the product to the shopping cart.

4. ### Shopping Cart

- **Description:** Manage products added to the shopping cart.
- **Requirements:**
  - Display a list of products added to the cart.
  - Allow users to update the quantity or remove products from the cart.
  - Show the total price of items in the cart.

5. ### Checkout Process

- **Description:** Implement a simple checkout process.
- **Requirements:**
  - Collect basic user information for the order (e.g., name, address).
  - Confirm order placement and show order summary.

6. ### State Management

- **Description:** Manage the app state using a basic state management solution.
- **Requirements:**
  - Use a simple state management approach such as setState or Provider.

7. ### Navigation

- **Description:** Implement navigation between screens.
- **Requirements:**
  - Use the Navigator for screen transitions.
  - Ensure smooth and intuitive navigation flow.

8. ### Error Handling

- **Description:** Handle and display error messages.
- **Requirements:**
  - Display error messages for network issues.
  - Validate form inputs and display appropriate error messages.

9. ### Unit Testing

- **Description:** Write basic unit tests for key functionalities.
- **Requirements:**
  - Write unit tests for authentication, API integration, and state management.

## Final Deliverables

- **Source Code:** Complete Flutter project source code for the app, named P1 Mobile App.
- Sample compiled application

- **Documentation:** README file including:
  - Setup instructions.
  - Explanation of the app architecture.
  - Description of key features and how to use them.
  - Details on adherence to best practices (DRY, TDD, separation of concerns).
- **Adherence to Best Practices:** The project must demonstrate adherence to software engineering best practices, including:
  - DRY (Don't Repeat Yourself) principle.
  - Test-Driven Development (TDD).
  - Separation of concerns.
