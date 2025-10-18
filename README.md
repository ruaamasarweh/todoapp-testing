  ### Hello and welcome to this Project.
This is a simple React Web application that was made for my blogs, where i will be using to explain a specific topics in Cypress.

# 📝 Todo Application - Manual Testing

This repository contains the **Todo Application** project along with its **Manual Testing** documentation.

## 🛡️ Quality Assurance & Testing

Comprehensive **Manual Testing** was conducted on the application to ensure all features function correctly and meet the requirements. This includes testing of:

- User authentication (signup, login, logout)
- Task creation, editing, and deletion
- Task completion and status updates
- UI/UX consistency across different devices

### Testing Artifacts

All detailed test results, including the executed **Test Cases** and the consolidated **Bug Report**, are documented and included in the uploaded Excel file:

* **Documentation File:** `QAcart Todo Application Checklist.xlsx` (located in the project root folder)

### Notes

- The test cases cover all main functionalities of the application.  
- Bugs found during testing are documented in the Excel file along with their status and priority.  
- This repository is maintained for **QA reference and further development**.  

---

> ⚠️ *Reminder:* This project is under continuous improvement, and testing will be updated as new features are added.


## Prerequisites:
This app is using mongodb as the databse, you will need to create a new mongo atlas clustor to be able to run the app. To do that you can find many videos on youtube just search for `create new mongo clustor on atlas`


## Run the App locally:
* Clone the repository.
* Download all the dependencies using `npm i` or `yarn install`
* Create .env file in the route folder.
* Add the below: 
```shell
MONGO_DB_URL=Your Mongo URL
TOKEN_SECRET=sahgjasbdasd
```
* To start the server `npm run start:server`
* To start the frontend `npm run start`
