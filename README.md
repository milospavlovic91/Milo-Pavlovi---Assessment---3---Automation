Automation Assessment - Miloš Pavlović

	This repository contains the solutions for the automation assessment, including both API tests and Selenium tests.

 Table of Contents
1. [API Tasks](#api-tasks)
2. [Selenium Tasks](#selenium-tasks)
3. [Setup Instructions](#setup-instructions)
4. [Usage Instructions](#usage-instructions)
5. [Contact](#contact)

API Tasks

Task 6
This task involves writing automated test cases for the provided APIs using Python and the Requests library.

#### Question 1: Retrieve Access Token
- **Function**: `get_access_token(email, password)`
- **Inputs**: Email, Password
- **Outputs**: Access Token, Time Taken

#### Question 2: Create User
- **Function**: `create_user(name, job)`
- **Inputs**: Name, Job
- **Outputs**: Name, Job, ID, Created At, Time Taken

#### Question 3: Update User
- **Function**: `update_user(user_id, name, job)`
- **Inputs**: User ID, Name, Job
- **Outputs**: Name, Job, ID, Updated At, Time Taken

#### Question 4: Delete User
- **Function**: `delete_user(user_id)`
- **Inputs**: NA
- **Outputs**: Time Taken


Selenium Tasks

Task 7
This task involves writing automated test cases for the provided interface using Python and Selenium.

#### Question 1: Log In to the Site
- **Function**: `login(driver, username, password)`
- **Description**: Logs into the site and verifies the login by checking the page title.

#### Question 2: Add and Remove Item from Cart
- **Function**: `add_item_to_cart_and_verify(driver, item_name)`
- **Description**: Adds an item to the cart, verifies its presence, removes it, and verifies its removal.

** Setup Instructions**

1. Clone the Repository
   ```bash
   git clone https://github.com/milospavlovic91/Milo-Pavlovi---Assessment---3---Automation.git
2.	Navigate to the Project Directory
bash
cd Milo-Pavlovi---Assessment---3---Automation
3.	Install Dependencies
bash
pip install -r requirements.txt

**Usage Instructions**
Running API Tests
1.	Navigate to the directory containing the API test scripts.
2.	Run the desired script using Python:
bash
python <script_name>.py
Running Selenium Tests
1.	Navigate to the directory containing the Selenium test scripts.
2.	Run the desired script using Python:
bash
python <script_name>.py

**Contact**
For any questions or additional information, please contact me at:
•	Email: pavlovicmpavlovic@gmail.com
Thank you for reviewing my automation assessment!

