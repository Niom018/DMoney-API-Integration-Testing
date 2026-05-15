# DMoney API Integration Testing - Batch 18

## Project Overview
This project demonstrates API Integration Testing using Postman for the DMoney Transaction API.

## Tested Workflow
- Admin Login
- Create Agent
- Create Customer 1
- Create Customer 2
- Activate Users
- System Deposit to Agent
- Agent Deposit to Customer
- Customer Send Money
- Customer Cashout

---

## Technologies Used
- Postman
- Newman
- Node.js
- HTML Extra Reporter

---

## Test Cases
Positive and negative test cases were implemented inside the Postman collection.

---

## API Documentation
[View API Documentation]https://documenter.getpostman.com/view/52207399/2sBXqQGdXK

---

## Newman Report
Newman HTML report is included inside the `Reports` folder.

## Newman Report Screenshot

![Newman Report](Screenshots/newman-report.png)

---

## Collection Run Result

![Collection Run](Screenshots/collection-run.png)

---

## API Documentation

![API Documentation](Screenshots/api-documentation.png)
---

## Important Notes
Some Newman assertion failures occurred due to dynamic OTP/token dependencies during automated execution.
However, the complete API workflow was tested successfully manually in Postman.

---

## Git Ignore Includes
- node_modules/
- Reports/
- .env

---

## Author
Niamul Hasan
Batch 18