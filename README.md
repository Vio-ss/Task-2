# Cucumber with BDD Example

This project demonstrates an example of using Cucumber with Behavior Driven Development (BDD) to test the login functionality of a web application.

# Cucumber with BDD Example

![img](https://github.com/Vio-ss/Task-2/assets/77194486/62a0cddd-df7b-4fee-8760-0f973dafa9a8)

## Features

### Feature: User Login with Valid and Invalid Credentials

This feature tests the user login functionality with various combinations of valid and invalid credentials.

### Scenario Outline: User login with valid and invalid credentials

This scenario outlines the steps for logging in with different combinations of credentials.

#### Given user launch browser

- The user launches the web browser.

#### When user check username "<username>" and password "<password>"

- The user checks the provided username and password.

#### And user validates url

- The user validates the URL of the web application.

### Examples

The scenario is executed with the following examples:

| username          | password     | 
|-------------------|--------------| 
| standard_user     | secret_sauce | 
| locked_out_user   | secret_sauce11 | 
| problem_user      | secret_sauce |
| performance_glitch_user | secret_sauce24 | 
| error_user        | secret_sauce | 
| visual_user       | secret_sauce62 | 

## Getting Started

To get started with the project, follow these instructions:

### Prerequisites

- Specify the prerequisites here (e.g., Cucumber, testing framework, browser drivers)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Vio-ss/Task-2
    ```

2. Navigate to the project directory:

### Usage

1. Execute the Cucumber tests for the login functionality.
