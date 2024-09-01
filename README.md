# OrangeHRM Employee Management Automation using TestNG

## Project Overview
This project automates the employee management process on the OrangeHRM demo site. The tasks include logging in as an admin, creating a new employee, verifying employee details, and updating personal information. The automation is implemented using TestNG, Selenium WebDriver, and Java.

## Prerequisites
- **Java 11** or above
- **Gradle** for dependency management
- **Selenium** for automation tool
- **Selenium** for automation framework (using POM)
- **IDE** like IntelliJ IDEA or Eclipse
- **Git** for version control

### How to Run This Project

1. **Clone the Project:**
   ```bash
   git clone https://github.com/your-github-username/orangehrm-employee-management-automation.git
   cd orangehrm-employee-management-automation
2. **Open in IntelliJ IDEA:**
   
3. **Build and Test:**   
   ```bash
   gradle clean test

4. **Generate Allure Report:**
   ```bash
   allure generate allure-results --clean -o allure-report

5. **View Allure Report:**
   ```bash
   allure serve allure-results

## Test Scenarios:
1. Login as Admin
   -  Authenticates as an admin and stores the token for further API requests.
   
2. Create Users:
   - Creates two new customers and one agent.
   - Go to the PIM menu and create a new employee.
   - Save the employee's firstname, lastname, employeeId, username, and password into a JSONArray file.
   - Generate a strong, random password that meets the following criteria:Combination of upper and lower case characters
   - Includes symbols and numbers
3. Assert that the employee is created successfully.
4. Transfer Money:
   - Transfers 2000 Tk from the system account to the newly created agent.
5.Deposit:
   - Deposits 1500 Tk from the agent's account to a customer's account.
6. Withdraw:
   - Withdraws 500 Tk from the customer back to the agent.
7. Send Money:
8. - Transfers 500 Tk from one customer to another.
9. Make Payment:
   - Processes a payment of 100 Tk to a specified merchant.
10. Check Balance:
   - Verifies the balance of the recipient customer after all transactions.
   
## Automation Showcasing:

## Allure Report:

